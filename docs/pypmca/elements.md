## [pypmca](index.md) Elements

​Each of the following sections describes the classes that
make up the pypmca population modelling engine.

## Model

A model object consisting of an ordered
set of connector objects that connect population objects.

The following takes place in order to calculate the evolution
by one time step:
* check if a transition needs to be applied, if so apply it
* for each connector (in order):
  * use the members incoming at the next time step
  to deduce the future contributions to
  connected population. In general this populates the
  futures of other populations. Since the connectors
  are treated in order, the effect of incoming populations
  near the start of the process can appropriately influence
  populations near the end of the process, if appropriate.
  * repeat through the full list of connectors

The default time_step length is 1 day. The initial release
for the ``ipypm`` user interface requires the time step
to be 1 day.
If working withe the ``pypmca`` package directly, shorter or
longer time steps are allowed.

The model can be built by writing python code that
creates the objects and adds them to the model, or
by using the [ipypm](../ipypm) graphical user interface.
An example of the code that produced reference model
#2 is found [here](https://github.com/pypm/pypmca/blob/master/examples/jupyter/ref_model_2.ipynb).

Important methods:

``reset()``
Returns the model to its initial state,
removing data from previous calculations.
This should be called before a new calculation is made.

``evolve_expectations(n_step)``
Calculates the expected size of each
population for n_step time steps.
The population objects store their expectedsize histories in the
``history`` instance variable.

``generate_data(n_step)``
Simulates the system by reporting outcomes of the integer random variables
that underly the connectors in the model.
The population objects store their size histories in the
same ``history`` instance variable that would be used for expectations.

``copy_values_from(from_model)``
This allows you to transfer the tuned values from the from_model to
a revised model (having the same names for parameters).

``save_file(filename)``
The model is saved to a file (typically < 50kB) that has all
information about the connections between populations and
all parameters and their values.
The filetype for a ``pyPM.ca`` model file is ``.pypm``.

``Model.open_file(filepath)``
Class method to restore a previously saved model. Returns a model object.

#### Booting a model

After resetting a model to initial state, the first step taken when
the next model evolution is requested is to boot the model
to arrive at t_0 with a steady state solution for all populations.
This ensures that the evolution beyond t_0 will continue a
steady state development, until the next transition.

The boot process deals with this, by starting with
small populations and evolve the system until a population exceeds
a target value. History is removed and the current populations and futures
are used for the initial state of the model. To allow for
continuous dependence, the current value and futures are scaled by the ratio of
the target value to actual value, except for the exclusion_populations.

The booting process is therefore defined by:
* boot_population: str, source population
* boot_value: float or int, small value to begin boot sequence.
* exclusion_populations: str or str-list of populations to exclude
from current value scaling. The history is set to the initial value for
the exclusion populations, the future contributions are scaled.

The boot sequence ends when the boot_population reaches or exceeds
the value set for the initial_value of that population.

## Population

A population class represents an identifiable
category that is useful to be tracked. Some populations are
necessary to describe the evolution of the system as a whole.
Others are created in order to define a population
that corresponds to category for which data exists.

After the expectations or simulation data are produced, the
population instance variable ``history`` is an python list
with length ``n_step+1``.

The populations are accessed through the populations dictionary
in the model.
For example the 'contagious' population history is accessed by:
``my_model.populations['contagious'].history``

## Connector

The ordered list of connector objects define the calculations
for the evolution of the system.
In general connectors take the incoming members
and distribute them to other populations
either all in the next time step, or
spread over time in the future, to represent a delay distribution.
There are several types of connectors:

#### Multiplier

A multiplier produces new members according to the product of
the sizes two populations (and optionally dividing by a third).
This defines the infection cycle of an epidemic as the number
of new infections is calculated to be the transmission rate (alpha)
times the product of the sizes of the suceptible and contagious
populations, divided by the size of the total population.

#### Propagator

A propagator distributes new members from one population
to one or more other populations.
If more than one population, this is done independently
when generating simulated data.

#### Splitter

A splitter divides a fraction of new members from one population
to two or more populations.
When generating simulated data, this is done by drawing
random numbers from a multinomial distribution, therefore
treating the dependence of the "to populations" correctly.

#### Chain

This connector combines several one-to-one propagators to and
sends the remainder to another population.
By combining these into a single connector the
dependence of the various populations involved are treated
correctly when generating data.

#### Adder

This is a simple connector that copies incoming members from
one population to another population immediately.
This is useful if two populations are needed to record
similar quantities, such as "hospitalized" - total number
admitted to hospital, and "in_hospital" - the number
in hospital that day. See "Subtractor".

#### Subtractor

This simple connector allows for members to be removed from a
population.
As patients in a hospital recover they are subtracted from
the "in_hospital" population, but not from the "hospitalized"
population".

## Parameter

Parameter objects are created for each parameter that may
affect the evoluton of the system.

Important methods:

``get_value()`` returns the current value

``set_value(value)`` sets the value

After changing the value of one or more parameters, 
you may want to recalculate the model evolution. As described
above this means:
```
my_model.reset()
my_model.evolve_expectations(n_step)
```

Parameters can be set to variable in order to identify
those which are to be tuned to best fit data.
The resulting values for the parameters are point
estimates.

Parameters are accessed through the ``parameters`` dictionary
in the model.
For example the current value of the
'alpha_0' parameter (the initial transmission rate)
is accessed by:
``my_model.parameters['alpha_0'].get_value()``

## Delay

Delay objects are created to describe the delay distribution
for the connectors.
The delay_type can be:
* ``fast``: immediate
* ``norm``: normal distribution, specified by a mean and standard deviation
* ``uniform``: uniform distribution
* ``erlang``: a distribution that corresponds to the convolution of
``k`` exponential random variables. This is included in case comparison
with ODE implementations are of interest, since ODEs can only
implement Erlang delay distributions.

## Transition

There are two types of transition objects (injector and modifier).
A transition occurs when the step counter reaches the
step specified by the transition object. At that step,
either a parameter value is changed or a set of members
is injected into a population.

#### Injector

An injector object will inject a set of members into a population.
Example uses are to model a burst of infections, such as seen
in Alberta and Saskatchewan in April and May 2020.

#### Modifier

A modifier object will cause the value of a parameter to change
at a particular time step.
Example usage includes the change in transmission rates that arise
when changes to social distancing rules are made.

## Ensemble

An ensemble object is a collection of models.
It allows for categorization of 
populations by age, risk, or other factors. It can also
be used to combine many models that may or may not be nearly independent
(such as separate provinces to make a Canada wide model).

Each category has its own model, and one model can influence the growth 
within other models.
The ensemble disables the infection cycle in each of the models
and performs the infection cycle which includes the mixing
between models, as specified by the contact_maxtrix.
The ensemble sums the histories of all its models to 
represent the evolution of
the entire system.
Like for a model, the ensemble population histories can be accessed through
the ensemble populations dictionary.

When mixing models having different growth rates, achieving the desired initial condition at t_0 through the
boot process is challenging. The boot process starts with a small number in each model's boot_population and
the boot ends when the ensemble exceeds its goal. It is possible that the relative sizes for each model
would differ significantly from the desired proportions, at t=0, and after scaling each model for the t_0 condition,
the state would be far from a steady state. A second boot can be done (by adjusting the small numbers in each model's
boot_population) according to the outcome from the first boot - ie. doing an iterative boot.
This issue is not as serious if, at least initially, the growth behaviours of the different groups are similar.

Owing to the complexity of ensembles made from mixtures of very different growth rate sub groups,
such situations should be treated with care until such behaviour has been thoroughly tested!

Important methods:

``save_file(filename)``
The ensemble is saved to a file that has all
information about the models and their connections 
The filetype for a ``pyPM.ca`` ensemble file is ``.pypm_e``.

``Ensemble.open_file(filepath)``
Class method to restore a previously saved ensemble. Returns an ensemble object.

``upload_models(list_of_models)`` and ``upload_model_files(list_of_files)`` 
adds models to the ensemble.

``define_cross_transmission(infection_cycle_name, infected_name,
susceptible_name, total_name, contagious_name, alpha_name,
contact_type, contact)`` defines how the populations mix and
gives sufficient information for the ensemble to replicate the
infection cycle.

For example new infections in model A arising from interactions with group B
are calculated by Susceptible_A / M * f[A][B] * Contagious_B * alpha_AB
* M is the total effective total population = sum f[A][B] * N_B.
* alpha_AB is the geometric mean = sqrt(alpha_A * alpha_B)
* the contact matrix, f, needs to be n x n, where n is the number of models
and the order of the matrix rows matches the order of the models in model_list

In a homogeneous society, all alphas are the same, 
and all terms of the matrix are 1.
f represents the relative probability for a contagious members of B group to infect a
random member of the A group (relative to infecting a random member of the B group).
The off diagonal elements are typically less than 1. The diagonal elements are 1 by
definition. A diagonal matrix describes a set of independent populations.
Given the definintion of M, both homogenous and independent populations yield their
original infection rate without adjusting alpha.

The contact matrix can be specified in a number of ways, defined by contact_type:
* 'diagonal','independent': all diagonal terms are 1, non-diagonal are 0.
This corresponds to the situation where all models develop independently
* 'equality': all matrix elements are 1.
This corresponds to the situation where members are blind to the catagorizations
* 'fixed': an arbitrary contact_matrix is provided as a list of list of floats
Diagonal elements are inforced to be 1. An ValueError is raised if not.
* 'simple': all off-diagonal elements are equal and specified by a single
Parameter object provided in list passed by the contact argument
* 'symmetric': off-diagonal elements passed by n(n-1)/2 Parameter objects
provided in the list passed by the contact argument - f12,f13,...,f1n,f23,f24...
Parameters are included in the ensemble parameter list for ease in adjusting the mixing.


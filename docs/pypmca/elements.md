## [pypmca](index.md) Elements

​Each of the following sections describes the classes that
make up the pypmca population modelling engine.

### Model

A model object consisting of an ordered
set of connector objects that connect population objects.

Important methods:

####``reset()``
Returns the model to its initial state,
removing data from previous calculations.
This should be called before a new calculation is made.

####``evolve_expectations(n_step)``
Calculates the expected size of each
population for n_step time steps.
The population objects store their expectedsize histories in the
``history`` instance variable.

####``generate_data(n_step)``
Simulates the system by reporting outcomes of the integer random variables
that underly the connectors in the model.
The population objects store their size histories in the
same ``history`` instance variable that would be used for expectations.

####``copy_values_from(from_model)``
This allows you to transfer the tuned values from the from_model to
a revised model (having the same names for parameters).

####``save_file(filename)``
The model is saved to a file (typically < 50kB) that has all
information about the connections between populations and
all parameters and their values.
The filetype for a ``pyPM.ca`` model file is ``.pypm``.

####``Model.open_file(filepath)''
Class method to restore a previously saved model. Returns a model object.


### Population

### Connector

#### Multiplier

#### Propagator

#### Splitter

#### Chain

#### Adder

#### Subtractor

### Parameter

### Delay

### Transition

#### Injector

#### Modifier

## pypmca Overview

The ``pypmca`` package is a general purpose framework
that models connected populations using
discrete-time difference equations. It was developed specifically
to understand and characterize the CoViD-19 epidemic.

### Populations and connectors

A ``pyPM.ca`` model is built by connecting a set of population objects with
connector objects. The connectors represent either a transfer that occurs
immediately at the next time step
or one which is delayed and distributed in time. Each
population object retains a record of its size at each time step, and also
maintains a list of future contributions, arising from delayed transfers
from other populations.
Calculations of population size are done either in terms of expectation values
or simulated data,
allowing the model to be used for both analysis and simulation.

### Transitions

Steady state solutions for these systems may develop. For viral epidemics these
solutions are exponential growth or decline of population size.
Systems perturbed by external influences, such as an instantaneous change
to a growth parameter or a sudden change in the size of a group,
may take time to relax to a new steady state solution.
The relaxation time depends on the various time delay distributions in the system.
To account for such perturbations, ``pyPM.ca`` models can include transition objects.

In order to model both long term and short term behaviour correctly,
realistic time delay distributions must be included.
This is achieved in ``pyPM.ca`` by using discrete-time difference equations,
in contrast to the ordinary differential equations (ODEs) approach
which form the foundation of the vast majority of epidemiological models.
The ODE approach is limited by its capability to introduce realistic time delays
and it offers no real benefit in modeling slowly evolving systems.

### Design

The ``pyPM.ca`` object oriented design makes it possible to create or modify a
connection network with little or no programming required, by using a suitable GUI.
A separate package, [ipypm](../ipypm/index.md)
provides a graphical user interface to ``pyPM.ca``
that runs inside a jupyter notebook.

### Heterogeneous systems

A single ``pyPM.ca`` model describes a homogenous system.
Heterogeneous systems can be modelled with an ensemble object,
by combining several ``pyPM.ca`` models, each
representing a distinct group or category, along with a contact matrix the represents
the engagement between the groups. Since an ensemble is a model object, tools that
interact with a model can also be used to interact with an ensemble.

## Documentation

* [Installation and startup](installation.md)
* [Elements of a pypmca model](elements.md)
* [MCMC analysis](mcmc.md)
* [Example applications](https://github.com/pypm/pypmca/tree/master/examples/jupyter)
* [ipypm](../ipypm/index.md) graphical user interface


## [return to pyPM.ca documentation home page](../..)


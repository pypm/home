## ipypm Overview
The `ipypm` package uses interactive python widgets (ipywidgets) to provide a graphical user interface
to the pypmca modelling engine.
It runs in a jupyter notebook, either on your computer (software installation required)
or on a jupyterhub server (no software installation required).

With `ipypm`, you can load models, explore their behaviour by adjusting parameters,
load data to confront the models, and perform basic parameter estimation by fitting models to the data.
The model structure itself can be edited through the GUI.

### Quickstart

Links are provided [here](https://github.com/pypm/quickstart)
to start `ipypm` with just a few clicks on Binder or a jupyter hub server.

### Local installation and startup

You can install the software on your own computer/server by following the instructions
[here](installation.md)

### Tabs

The `ipypm` interface is divided into tabs. Only the Open and Edit tabs are shown when you start.
After you load a model to work with, the other tabs will appear:

* [Open](open.md): Loading models and data
* [Settings](settings.md): Selecting what is visible
* [Explore](explore.md): Exploring models with data
* [Analyze](analyze.md): Fitting models to data (estimating model parameters)
* [MCMC](mcmc.md): Using MCMC methods to estimate uncertainty bands in future projections
* [Compare](compare.md): Comparing two models side-by-side
* [Edit](edit.md): Examining a model in detail and making changes to its structure.

### Advanced analyses

You can develop analyses in the jupyter notebook by
interacting with the models and data being used by ipypm.
Documentation for this will be provided soon.

## [return to pyPM.ca documentation home page](../..)


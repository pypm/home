## [ipypm](index.md) - Edit tab

The Edit tab lets you explore the model in detail, showing each element. You can change the structure of the model,
by adding new populations and connections between them.

The model being edited is read in in the Edit_Model tab. It is independent of the models used in other tabs.

The objects that make up the model are grouped according to the classes in the `pypmca` package:
Parameters, Delays, Populations, Connectors, and Transitions.
For each of the tabs, you need to click refresh to populate the dropdown boxes.

You can see all objects of a class by clicking on the Table button within the tab. Some examples are shown below for the
reference model #2.

### Parameters:

![edit-parameter](img/edit-parameter.png)

### Populations:

![edit-population](img/edit-population.png)

### Propagators:

![edit-propagator](img/edit-propagator.png)

### Transitions:

![edit-transition](img/edit-transition.png)

The conditions that define the boot sequence (see `pypmca` documentation) are set in the Edit-Boot tab.

MOST
====

A foundation library for implementing a simple model-view-controller (MVC) architecture using the MATLAB object system and (currently) the GUIDE app building system. 

Compared to at least one other [reference MVC architecture](https://www.mathworks.com/company/technical-articles/developing-matlab-apps-using-the-model-view-controller-pattern.html) in MATLAB which may emphasize app responsiveness/pleasantness, this library is focused on minimizing coding time for 'hooking up' an app's user interface to its rich feature set which is made equally available at the command-line. 

Library also includes:
* property validation for model (command-line) object (note: this was implemented before MATLAB's [property validation capabilities](https://www.mathworks.com/help/matlab/matlab_oop/validate-property-values.html) were introduced)
* settings file load/save functions for saving/restoring app's state (note: in contrast to built-in [object load & save](https://www.mathworks.com/help/matlab/save-and-load.html) functionality, properties can be set in a specified order & property subset files can be saved/loaded)

#### Janelia Contributors
* Vijay Iyer (initial concept & implementation)
* Allen Lee (refined concept & implementation) 
* Frank Midgley (initial testing)


Copyright 2023 by the Howard Hughes Medical Institute.
All rights reserved.

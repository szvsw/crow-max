# Crow :: Max and Max4Live Patches


## /crow/

Place this entire directory in your Max libraries folder. 

Contains the *crow.maxpat* object for connecting to Crow.  


*/crow/help/* contains a work-in-progress *crow.maxhelp* file which will be opened using the standard Max help/reference keyboard shortcut on the crow object.

*/crow/docs/* contains the necessary files for Max to populate the reference page/helpfile for Crow and include digest information in Max's object search.


## /m4l/

Place this directory wherever you like to keep your Ableton Max for Live devices.  

Contains the work-in-progress *crow.amxd* M4L device, which requires *crow.maxpat* to either be in your Max Library or in the same directory as the M4L device.

## To Do

[*crow.amxd issues*](https://github.com/whimsical-sam/crow-max/issues?q=is%3Aissue+is%3Aopen+label%3Am4l)




*crow.maxhelp*

* Update *out[n]* to *output[n]* once new firmware installed on Crow
* Better visualization on inputs tab.
* Entire outputs tab (suggest self-patching Crow to visualize outputs in Max)
* Entire metros tab
* Add I2C tab
* Once script-loading bug is repaired in crowmax.lua, sript-loading tab.

# IMS2 Distribution package

IMS2 is an add-on for Orbiter 2016 that allows players to build their own spacecraft in the simulation.
This is the distribution package, containing all files neccessary to run the add-on in Orbiter, save for external dependencies (see installation).

## Current version:
Alpha-1

## Installation
[Download and install SSBB 4.1](http://www.orbithangar.com/searchid.php?ID=3177)  
[Download the IMS2 distribution package](https://github.com/TheNewBob/IMS2-Distribution/archive/master.zip) 
[...Or Download the latest unstable version](https://github.com/TheNewBob/IMS2-Distribution/archive/develop.zip) 
Open the zip file and unpack the contents of IMS2-Distribution-master/Orbiter into your orbiter 2016 directory.

## Manual

This is an Alpha version, so there isn't yet a definite user manual available.  
You can find a user-oriented documentaion of usage and current features [here](http://orbiter-forum.com/group.php?do=discuss&group=&discussionid=463), though.

## Dependencies

IMS2 requires the following prerequisites to run properly:

[Orbiter 2016 by Martin Schweiger](http://orbit.medphys.ucl.ac.uk/)  
[Spacestation Building Blocks 4.1 by Greg Burch](http://orbit.medphys.ucl.ac.uk/)

## Recommended add-ons
IMS2 comes with a toolbox set for the [Orbiter StackEditor](http://www.orbithangar.com/search_quick.php?text=stackeditor&submit.x=0&submit.y=0), which is a much more convenient tool
to put vessels together than Scenario Editor. It does come with a few caveats for Orbiter 2016, however:  
* StackEditor has no extended support for IMS2 modules, i.e. it will not display any module properties.
* StackEditor hangs when exporting the vessel to Orbiter. The vessel is still exported, but StackEditor will be unresponsive afterwards.
* IMS2 is likely to crash when using the "integrate all" feature immediately after the vessel is spawned by StackEditor.
the best course of action is to spawn the vessel, quit orbiter, and then restart the current state.
* StackEditor will spawn vessels at the center of the sun.

These issues are not IMS2 related, and will not immediately be fixed in StackEditor. An adaptation of StackEditor specifically for IMS2 is planned for the Beta-stage, all issues will be addressed at that point.

After installing StackEditor, you'll have to open StackEditor/StackEditor.cfg and change the line:  
`tbxset = default` 
to 
`tbxset = IMS2`

## Source code

The source code of IMS2 is available [here](https://github.com/TheNewBob/IMS2).




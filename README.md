# IMS2 Distribution package

IMS2 is an add-on for Orbiter 2016 that allows players to build their own spacecraft in the simulation.
This is the distribution package, containing all files neccessary to run the add-on in Orbiter, save for external dependencies (see installation).

## Current version:
Alpha-1

## Installation
[Download and install SSBB 4.1](http://www.orbithangar.com/searchid.php?ID=3177)  
[Download the IMS2 distribution package](https://github.com/TheNewBob/IMS2-Distribution/archive/master.zip)  
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


## File list

The package contains the following files:
```
Orbiter/Config/IMS2/Consumables.cfg
Orbiter/Config/Vessels/IMS2/Communications/BCM101_Antenna.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BCP01_Cupola.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM001_Small_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM002_Small_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM004_Small_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM010_Small_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM011_Small_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM012_Small_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM013_Small_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM101_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM102_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM103_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM104_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM110_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM111_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM112_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM201_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM202_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM203_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM204_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM211_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM212_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM213_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM214_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM215_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM216_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BM222_Habitat.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BN101__Node.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BN200_Big_Node.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BN201_Big_Node.cfg
Orbiter/Config/Vessels/IMS2/Habitat/BN301_Trussed_Node.cfg
Orbiter/Config/Vessels/IMS2/Habitat/Cover.cfg
Orbiter/Config/Vessels/IMS2/Habitat/Cover_small.cfg
Orbiter/Config/Vessels/IMS2/Landing_Gear/BTDL_Landing_Leg.cfg
Orbiter/Config/Vessels/IMS2/Propulsion/BHVE_SideMount_Rocket.cfg
Orbiter/Config/Vessels/IMS2/Propulsion/BRCS1_ReactionControlSystem_Engine.cfg
Orbiter/Config/Vessels/IMS2/Propulsion/BRCS2_ReactionControlSystem_Engine.cfg
Orbiter/Config/Vessels/IMS2/Propulsion/BRCS3_Methane_RCS_Engine.cfg
Orbiter/Config/Vessels/IMS2/Propulsion/BRCS4_Methane_RCS_Engine.cfg
Orbiter/Config/Vessels/IMS2/Propulsion/GasCoreNTR_ClosedCycle.cfg
Orbiter/Config/Vessels/IMS2/Propulsion/J-2XIM_Rocket_Engine.cfg
Orbiter/Config/Vessels/IMS2/Propulsion/NERVA.cfg
Orbiter/Config/Vessels/IMS2/Propulsion/Test_engine.cfg
Orbiter/Config/Vessels/IMS2/Propulsion/VASIMR_10MW.cfg
Orbiter/Config/Vessels/IMS2/Propulsion/VASIMR_4MW.cfg
Orbiter/Config/Vessels/IMS2/Tank/BTank101_LH2_Large.cfg
Orbiter/Config/Vessels/IMS2/Tank/BTank102_CH4_Large.cfg
Orbiter/Config/Vessels/IMS2/Tank/BTank103_LOX_Large.cfg
Orbiter/Config/Vessels/IMS2/Tank/BTank104_RP1_Large.cfg
Orbiter/Config/Vessels/IMS2/Tank/BTank201_N2H4_Small.cfg
Orbiter/Config/Vessels/IMS2/Tank/BTank202_CH4_Small.cfg
Orbiter/Config/Vessels/IMS2/Tank/BTank203_LOX_Small.cfg
Orbiter/Config/Vessels/IMS2/Tank/BTank204_LOX_LCH4_Small.cfg
Orbiter/Config/Vessels/IMS2/Tank/Tank_CH4_XL.cfg
Orbiter/Config/Vessels/IMS2/Tank/Tank_LH2_XL.cfg
Orbiter/Config/Vessels/IMS2/Tank/Tank_LOX_RP1_ratio-2.56-1_XL.cfg
Orbiter/Config/Vessels/IMS2/Tank/Tank_LOX_XL.cfg
Orbiter/Config/Vessels/IMS2/Tank/Tank_RP1_XL.cfg
Orbiter/Config/Vessels/IMS2/Truss/BCPLR_UniCoupler.cfg
Orbiter/Config/Vessels/IMS2/Truss/BT1001_Truss.cfg
Orbiter/Config/Vessels/IMS2/Truss/BT100_Truss.cfg
Orbiter/Config/Vessels/IMS2/Truss/BT1011_Truss.cfg
Orbiter/Config/Vessels/IMS2/Truss/BT101_Truss.cfg
Orbiter/Config/Vessels/IMS2/Truss/BT102_Node.cfg
Orbiter/Config/Vessels/IMS2/Truss/BT201_Truss_to_Module_Adapter.cfg
Orbiter/Config/Vessels/IMS2/Truss/BT301_LargeTrussToSmallTruss.cfg
Orbiter/Config/Vessels/IMS2/Truss/BT302_LargeTrussToSmallTruss_Short.cfg
Orbiter/Config/Vessels/IMS2/Truss/Truss_15m.cfg
Orbiter/Config/Vessels/IMS2/Truss/Truss_1to3.cfg
Orbiter/Config/Vessels/IMS2/Truss/Truss_21m.cfg
Orbiter/Config/Vessels/IMS2/Truss/Truss_fork.cfg
Orbiter/Config/Vessels/IMS2/Truss/Truss_light_15m.cfg
Orbiter/Config/Vessels/IMS2/Truss/Truss_light_1to3.cfg
Orbiter/Config/Vessels/IMS2/Truss/Truss_light_21m.cfg
Orbiter/Config/Vessels/IMS2/Truss/Truss_light_fork.cfg
Orbiter/Meshes/IMS/APAS_Docking_Port.msh
Orbiter/Meshes/IMS/BCCH.msh
Orbiter/Meshes/IMS/BCFGA.msh
Orbiter/Meshes/IMS/BCPLR.msh
Orbiter/Meshes/IMS/BHVE.msh
Orbiter/Meshes/IMS/BNTRGCCC.msh
Orbiter/Meshes/IMS/BR010.msh
Orbiter/Meshes/IMS/BR020.msh
Orbiter/Meshes/IMS/BR200.msh
Orbiter/Meshes/IMS/BRCS.msh
Orbiter/Meshes/IMS/BRCS2.msh
Orbiter/Meshes/IMS/BT1001.msh
Orbiter/Meshes/IMS/BT1011.msh
Orbiter/Meshes/IMS/BTDL.msh
Orbiter/Meshes/IMS/CBM_Docking_Port.msh
Orbiter/Meshes/IMS/DADG.msh
Orbiter/Meshes/IMS/FuelTank_New.msh
Orbiter/Meshes/IMS/HPE.msh
Orbiter/Meshes/IMS/J-2XIM.msh
Orbiter/Meshes/IMS/NERVA.msh
Orbiter/Meshes/IMS/SSBBLargeTrussToSmallTruss.msh
Orbiter/Meshes/IMS/SSBBLargeTrussToSmallTrussShort.msh
Orbiter/Meshes/IMS/Truss1to3.msh
Orbiter/Meshes/IMS/Truss_15m.msh
Orbiter/Meshes/IMS/Truss_21m.msh
Orbiter/Meshes/IMS/Truss_fork.msh
Orbiter/Meshes/IMS/Truss_fork_light.msh
Orbiter/Meshes/IMS/Truss_light_15m.msh
Orbiter/Meshes/IMS/Truss_light_1to3.msh
Orbiter/Meshes/IMS/Truss_light_21m.msh
Orbiter/Meshes/IMS/Trussnode.msh
Orbiter/Meshes/IMS/VASIMR.msh
Orbiter/Meshes/IMS/VASIMR_4MW.msh
Orbiter/Meshes/IMS/cover.msh
Orbiter/Meshes/IMS/cover_small.msh
Orbiter/Modules/IMS2/IMS2.dll
Orbiter/Scenarios/IMS2/Plato Base.scn
Orbiter/Scenarios/IMS2/moonhopper at brighton beach.scn
Orbiter/StackEditor/Toolboxes/IMS2/Comms.tbx
Orbiter/StackEditor/Toolboxes/IMS2/Habitat.tbx
Orbiter/StackEditor/Toolboxes/IMS2/Landing_Gear.tbx
Orbiter/StackEditor/Toolboxes/IMS2/Propulsion.tbx
Orbiter/StackEditor/Toolboxes/IMS2/Tanks.tbx
Orbiter/StackEditor/Toolboxes/IMS2/Truss.tbx
Orbiter/Textures/IMS/BCCH.dds
Orbiter/Textures/IMS/BCFGA.dds
Orbiter/Textures/IMS/BCLPR1.dds
Orbiter/Textures/IMS/BCover.dds
Orbiter/Textures/IMS/BNP.dds
Orbiter/Textures/IMS/BNTRGCCC.dds
Orbiter/Textures/IMS/BR200.dds
Orbiter/Textures/IMS/BRCS.dds
Orbiter/Textures/IMS/CBM_Docking_Port.dds
Orbiter/Textures/IMS/DADG.dds
Orbiter/Textures/IMS/FuelTank.dds
Orbiter/Textures/IMS/HPE.dds
Orbiter/Textures/IMS/Misc.dds
Orbiter/Textures/IMS/NERVA.dds
Orbiter/Textures/IMS/NTR.dds
Orbiter/Textures/IMS/NTR2.dds
Orbiter/Textures/IMS/NTR3.dds
Orbiter/Textures/IMS/RS-68.dds
Orbiter/Textures/IMS/SSBBLargeTrussToSmallTruss.dds
Orbiter/Textures/IMS/Truss.dds
Orbiter/Textures/IMS/VASIMR.dds
Orbiter/Textures/IMS/blanketlight.dds
Orbiter/Textures/IMS/texture.dds
README.md
```

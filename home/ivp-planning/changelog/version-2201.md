# Version 2201

![](../../../.gitbook/assets/2201.jpg)

## Version 2201.0
_2022-01-28_

### Added

* Tag search in the machine library
* Hierarchy: Objects now move, rotate, scale, lock and hide with their parent
* Implemented a new save file format: saving and loading is now faster and more robust (old save files can still be loaded)
* Added an option to open the auto save folder from within iVP

### Changed

* Reworked user interface
  * Improved visual appearance
  * Improved usability of docking panels
* Improved object scaling workflow
  * Objects can now also be scaled from the customization panel
  * Objects can now also be scaled on the z-axis
* Rearranged the library according to your suggestions
* Improved 3D view camera navigation
  * Added a navigation gizmo, that allows viewing your plan from an axis aligned perspective and in an isometric view
  * Added panning
  * Added zooming
* Reduced application startup time

### Fixed

* Performance improvements for machines in the Schuler library
* Various other bugfixes and performance improvements

## Version 2201.0.1
_2022-02-04_

### Changed

* Reduced application size
* Reintroduced the reset camera position button in the 3D view

### Fixed

* Scale/Mirroring is not applied when loading a save file
* Some CNC machines are not correctly loaded from legacy save files
* Some CNC machine's customizations have wrong translations
* The grid in the 2D view does not update correctly when zooming
* The documentation can not be opened via Help > Documentation
* Machines can not be placed inside a path
* Pressing the confirm button when saving does not actually save the plan
* Robot (with linear axis) changes it's position when it's mirrored
* Locked machines are not visible in the 2D view when overhead view is enabled

## Version 2201.0.2
_2022-02-17_

### Fixed

* Visual representation of some machines
* Visual representation of some UI elements
* Some machines that should not be mirrored can be mirrored
* Transformation values set in the properties panel are reverted when moving an object in 3D view directly after the modification
* Objects do not save their parent object and position correctly under certain conditions

## Version 2201.1
_2022-03-17_

![](../../../.gitbook/assets/version-2201-1.png)

### Added

* SAWTEQ B-300 (HXX 300) with customizations
* SAWTEQ B-400 (HXX 400) with customizations
* SAWTEQ B-100 as static model
* SORTEQ R-300 (RKS 200)
* DRILLTEQ H-308
* DRILLTEQ H-310
* ChainConveyor / Kettenförderer (THK 500)
* CENTATEQ C-100 with customiztaions
* TLF bridge as single model with length
* Added alias functionality for SAWTEQ (HKL, HPP, HPL)

### Fixed

* Loading .hfc savefiles older than March 2021
* Mirrored machine incorrectly loaded when parent is mirrored
* Storage Good tab of Pallet Rack does not work anymore
* Machines using MeshCombineStudio sometimes throw an Exception when loading
* Textobject was not loaded properly
* 2D and 3D visual are mirrored

### Changed

* Old SAWTEQ B-300 and B-400 are hidden now
* Tablet has customizable displays
* Single SORTBOT R-300 rack has customizable sizes
# Version 2310

## Version 2310.0
_2023-10-27_

### Added

* PDFs are now imported with the new import pipeline, which has the following advantages
    * PDFs can now be moved freely
    * The PDFs size is now correctly fetched from the file
    * PDF tiling, scale, padding and transparency can be configured at any time
    * Added the option to replace a color with transparency
* Edge lengths and angles of paths can now be modified from the properties panel of a path point
* You can now choose to not load or delete downloaded bundles
* A progress bar is now displayed for each bundle that is being downloaded
* Added a toggle to include objects from bundles that aren't currently loaded in the results when searching in the library panel
* Added a toggle that controls the orientation (global/local space) of the 3D gizmo to the header of the 3D view panel
* It is now possible to undo moving a path point

### Changed

* Replaced the backend used for glTF/glb import. This has the following benefits
    * The import is now less error prone
    * The import is now way faster
    * Importing files with external resources, such as textures, is now supported
* Imported images now allow to set the tiling of the x/y axis independently
* Imported images now have the following additional options:
    * Scale
    * Padding
    * Replace a color with transparency
* When placing an object, it is now previewed in the 2D & 3D view and can be rotated with the scroll wheel
* The legacy versions of the EDGETEQ S-300 & S-380 (the ones without customizations) are no longer shown in the library

### Fixed

* The application no longer sometimes crashes when importing files in the glTF/glb format
* Imported files are no longer sometimes missing from saved plan files under rare circumstances
* Imported models no longer have the wrong rotation when they were saved with a non-zero rotation
* Imported models no longer block the selection of other objects when they are disabled
* The download of bundles no longer fails when downloading more than 10 bundles at the same time
* The application now starts up correctly when a VR headset is connected and no internet connection is available
* The roller conveyor (TFR-561) once again shows the correct values for working height, in- and outfeed when working with more than one level
* Ceilings and floors of rooms created with the path tool are no longer offset after centering a paths pivot
* Loading paths from legacy save files (.hfc) no longer sometimes fails
* Saving a screenshot no longer fails when choosing a file extension with capital letters
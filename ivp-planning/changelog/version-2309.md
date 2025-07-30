# Version 2309

## Version 2309.0
_2023-09-13_

### Added

* 3D data import (in Beta for selected users)
* Plan file import
* Local library for imported files

### Changed

* Unified import of images, DXFs, plans and 3D models into a single import button (File > Import)
* The progress bar now shows what is currently being loaded
* You can now decide to save an imported file inside your plan file at any time
* The Text Object now rotates it's text towards the recording camera during video export when the "Text looks at Camera" option is enabled
* The properties panel now updates it's text immediately when the language is changed

### Fixed

* The floor plan PDF is no longer displayed above placed objects in the 2D view

## Version 2309.0.1
_2023-09-18_

### Fixed

* Searching through your library once again works as expected when you don't have a local library
* When an object you copied to your local library manually is placed for the first time, it's default values are now correctly auto generated and you can edit them in the properties panel

## Version 2309.1
_2023-09-20_

### Added

* PDFs are now imported with the new import pipeline, which has the following advantages
    * PDFs can now be moved freely
    * PDF tiling, scale, padding and transparency can be configured at any time
    * Added the option to replace white backgrounds with transparency
* Edge lengths of paths can now be modified from the properties panel of a path point, giving you precise control of the length
* Added a toggle that controls the orientation (global/local space) of the 3D gizmo to the header of the 3D view panel

### Changed

* Replaced the backend used for glTF/glb import. This has the following benefits
    * The import is now less error prone
    * The import is now way faster
    * Importing files with external resources, such as textures, is now supported
* Imported images now allow to set the tiling for the x/y axis independently
* Imported images now have the following additional options:
    * Tiling
    * Scale
    * Padding
    * Transparency
    * Use white as transparency

### Fixed

* The application no longer sometimes crashes when importing files in the glTF/glb format
* Imported models no longer have the wrong rotation when they were saved with a non-zero rotation

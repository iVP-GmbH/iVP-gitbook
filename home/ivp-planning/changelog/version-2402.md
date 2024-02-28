# Version 2402

## Version 2402.0
_2024-02-28_

### Added

* Support for importing a skybox from an image
* High quality renderings of plan files can now be rendered in the cloud (in testing phase for selected users)
* Materials of imported glTF files are now replaced with matching materials based on their material slot. The materials that will be used are user configurable.
* Recently opened files are saved and suggested for opening in the file menu
* It is now possible to select an objects parent with a keyboard shortcut (Y)
* It is now possible to open the corresponding documentation page from the 2D, 3D and hierarchy and library panel
* FBX models with external textures are now supported
* You will now get notified when there is a new version of iVP Planning available

### Changed

* When multiple objects overlap in the 3D or 2D view, clicking the same position multiple times now cycles through the objects that are eligible for selection
* When clicking an object that is inside an imported plan, the plan is selected on the first click. Clicking the same object again selects the object itself
* The position, rotation and scale of objects are no longer updated while changing their values in the inspector
* Changing position, rotation and scale of objects in the inspector can now be undone
* Improved visual appearance of metallic materials

### Fixed

* The application no longer sometimes crashes when working with imported 3D files that are not in the glTF format
* Importing non glTF models with a capitalized file extension no longer fails
* When duplicating an imported plan file, the objects in the file now do get highlighted correctly when the file is selected
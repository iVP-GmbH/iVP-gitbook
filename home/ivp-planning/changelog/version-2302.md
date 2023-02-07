# Version 2302

## Version 2302.0

### Added

* User management
    * Sign in with Microsoft Azure Account
    * Ability to restrict features to specific user groups
    * Ability to restrict objects in the library to specific user groups
    * Replaces the license management using a license key
* DXF Import/Export (restricted to specific user groups)
* Image import (restricted to specific user groups)
* Many new non-branded assets (restricted to specific user groups)
* Added color presets to the color selection (restricted to specific user groups)
* New units centimeter & decimeter

### Changed

* When overwriting a save file, no data is modified when saving fails
* In the color picker, colors can now also be entered via the input fields (as RGB or HSV)
* The color pickers color profile button now shows the currently selected color profile
* Objects can now also be renamed by double clicking their entry in the hierarchy
* The warning message in the properties panel that is displayed when an object is scaled now has a button to reset the scale
* Added limits to the customizations of various objects
* Removed option to import databases
* The _Help > Documentation_ button now opens Plannings documentation page instead of the Help Desks main page

### Fixed

* When loading the same plan file additively twice and saving afterwards, the hierarchy is now preserved
* When selecting objects they no longer "stick" to the mouse pointer under certain conditions
* The perspective gizmo in the 3D view no longer stops moving the camera before the target position is reached under certain conditions
* Focusing small objects now moves the camera to the correct position
* When clicking on a foldout menu in the _File_ menu (top left), the menu is no longer closed
* Renaming an object from the hierarchy no longer sometimes fails
* While renaming an object in the hierarchy, clicking in the text no longer ends the renaming process
* LOOPTEQ O-300 can now also be customized when hidden
* When editing a Text Object while it is hidden, it's bounds now have the correct size
* Pallet Rack (Universal) now also shows it's tooltips when the english locale is selected
* When duplicating certain machines and deleting the orignal afterwars, the duplicate no longer have missing parts
* Storage good specific customizations of Load Carrier (Universal) & Pallet Rack now do get propagated correctly when duplicating
* When placing a virtual camera, it is now visible in the preview
* All texts in the color picker now use the correct font
* Various minor bugfixes
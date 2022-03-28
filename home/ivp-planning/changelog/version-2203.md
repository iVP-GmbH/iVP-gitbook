# Version 2203

## Version 2203.0 - 2022-03-29

### Added

* Paths are now displayed in the hierarchy instead of a separate panel
* Path transform and customizations are now displayed in the properties panel
* Paths can now be selected like machines
* Ability to copy/paste paths
* Paths can now be parented
* Paths can now be hidden
* Paths can now be locked
* Paths can now be scaled
* Path label font size is now customizable
* Path modules can now be selected and customized:
    * All modules
        * Type
        * Anchor
        * Position
        * Width
    * Door in fence
        * Model (swinging or sliding door)
    * Passthrough in fence
        * Upper edge height
        * Fence below on/off
        * Lower edge height
        * Finger protection on/off
        * Finger protection depth
    * Door in room
        * Height
    * Passthrough in room
        * Upper edge height
        * Lower edge height
    * Window in room
        * Upper edge height
        * Lower edge height
* Added customizable fence module in fences
* Added Window module in rooms
* Added Lightbarrier module in fences
* Paths can now be drawn in 3D view
* Path labels are now visible in 3D view
* Path name labels can now be hidden
* Text objects and geometric bodies now have dedicated icons in the hierarchy
* Added a warning message when an object is scaled

### Changed

* Path modules can now be placed everywhere on an edge instead of only next to a point
* Path modules can now be moved on their edge
* Improved path's visual appearance
* Context menus now also work in 3D view
* When a path is a marking, the area is now enabled by default
* Increased 3D gizmo size
* Updated database tags
* Smart Hardware Set tablet display can now be customized and defaults to cutting plan

### Fixed

* Scrollbars now correctly enforce a minimal height
* Paths now show the correct visibility state when loaded
* When inserting a point into a path, the new point is now always exactly on the line
* When renaming a virtual camera in the camera list, it now correctly updates it's name in the hierarchy aswell
* Various minor bugfixes
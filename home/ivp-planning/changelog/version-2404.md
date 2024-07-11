# Version 2404

## Version 2404.0
_2024-07-10_

### Added

* External 3D models can now be converted and simplified in the cloud (in testing phase for selected users)
* New cloud panel (Window > Cloud) for up- and downloading files for cloud services (in testing phase for selected users)
* Add support for importing HDR images/skyboxes
* The skybox can now optionally be used as a reflection source
* New machine: CENTATEQ P-100
* New machine: CENTATEQ P-610
* Sorting shelf: New sizes

### Changed

* The login flow has been completely rewritten to be more robust and faster. As a result of this, you will reauthenticate when launching the application for the first time after the update.
* Materials and textures can now be updated independently of the content bundles. This means big updates of your library will happen less frequently. To make this possible, all bundles will have to be updated one last time.
* Opting in/out of analytics has been simplified. This can now be done by simply flipping a toggle in the settings. No external website is required anymore.
* The _show_ toggle in the skybox panel is no longer enabled automatically each time you open the panel. This now only happens when you change the image path.
* Improved visual appearance of tab group headers (settings panel and cloud panel)
* Adjusted the icon and wording of the button that saves an image in the screenshot annotation mode

### Fixed

* The bounding box of paths in the 2D panel is no longer incorrect when their points have been moved
* The bounding box of objects in the 2D panel is no longer incorrect when they've been rotated around the x- or z-axis
* Setting the position of a path point from the inspector no longer results in the point being moved to a wrong position when the grid origin is not set to center
* Imported images are no longer invisible in the 2D view when locked and the overhead view is disabled
* Focusing (F) a point of a path once again moves the camera close to the point instead of very far away from it
* The floor is no longer being clipped (partially invisible) in the 3D view in orthographic mode from certain camera angles
* Paths can now be converted to ground paths from the context menu
* Analytics once again work
* Switching a path between room and fence type once again keeps the customizations that are specific to the respective type
* Light Barriers in fences created using the path tool no longer change their material when the fence material is changed
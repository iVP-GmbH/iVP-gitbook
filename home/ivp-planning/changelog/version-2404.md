# Version 2404

## Version 2404.0

### Added

* External 3D models can now be converted and simplified in the cloud (in testing phase for selected users)
* New cloud panel (Window > Cloud) for up- and downloading files for cloud services (in testing phase for selected users)

### Changed

* The login flow has been completely rewritten to be more robust and faster. As a result of this, you will reauthenticate when launching the application for the first time after the update.
* Materials and textures can now be updated independently of the content bundles. This means big updates of your library will happen less frequently. To make this possible, all bundles will have to be updated one last time.
* Opting in/out of analytics has been simplified. This can now be done by simply flipping a toggle in the settings. No external website is required anymore.
* To _show_ toggle in the skybox panel is no longer enabled automatically each time you open the panel. This now only happens when you change the image path.
* Improved visual appearance of tab group headers (settings panel and cloud panel)

### Fixed

* The floor is no longer being clipped (partially invisible) in the 3D view in orthographic mode from certain camera angles
* Analytics once again work

# Version 2209

![](../../../.gitbook/assets/2209.png)

## Version 2209.0 - 2022-09-22

### Added

* Markup tool

### Changed

* In the 2D view, zoom speed is now dependent on the distance to the floor (you zoom slower when you're already close to the floor)
* Belt conveyor (TFB 100) now has a raster for it's working width
* Removed offline changelog & open source license panel in favor of web version

### Fixed

* Panning in the 2D and 3D orthographic view now moves you exactly by the amount you'd expect
* SAWTEQ B-200 power concept is no longer missing
* SAWTEQ B-200 lifting table variants is no longer missing
* SAWTEQ B-300 micro inserts are no longer missing
* SAWTEQ B-130/180/200 label printers do now show the right model
* SAWTEQ B-200 module45 dependencies are now working correctly
* Switching language doesn't fail anymore under certain conditions
* DRILLTEQ L-200 does not show the wrong customization in 2D view when loaded from a save file anymore
* Loading a mirrored SORTEQ R-200 from a save file now works as expected
* Box selection (2D view) now also affects objects beneath the floor
* Resizing mirrored objects using the handles in the 2D view no longer moves the object to the wrong position
* Dragging on labels of input fields in the properties window now applies the modified values
* Path distance labels are now longer clipping into the floor
* When duplicating a SORTEQ R-200 and modifiying the duplicate, the originals rods no longer disappear
* Renaming machines from the properties window once again works
* The bug reporting panel once again highlights empty mandatory fields when trying to send an invalid report
* Various minor fixes on machines

## Version 2209.1 - 2022-10-18

### Added

* New customization _Transport_ in measure station

### Changed

* Replaced SAWTEQ B-300 Robin with new SAWTEQ B-300 FlexTec (HPX 300) with many new customizations
* Display terminal without gallow when only one module is enabled in switch cabinet
* Removed deprecated version of belt conveyor TFB-261

### Fixed

* Modifying values of input fields in the customization panel no longer sometimes results in wrong values
* The tag search once again displays the correct text for 'Filter by tag'
* The scale of the 3D-volume scanner is now correct
* The WALLTEQ M-310 is now correctly moved to it's rails when the rail length changes while animated
* The PDF information of the SAWTEQ B-300 no longer clips into the floor
* When switching language, the toggles displaying the currently selected language do now always update


## Version 2209.2 - 2022-11-16

### Added

* Handling table
* SORTBOT R-300 (RKS 300)
* New customizations _Handling Table_, _Stacking Height_ & _Remote Control Cabinet_ in PAQTEQ C-250
* New customizations _Terminal_ & _Control Cabinet_ in PAQTEQ S-200
* New customization _Handling Table_ in DRILLTEQ C-300/500/600/800

### Changed

* Removed customization _Machine Orientation_ from SAWTEQ B-300 flexTec (HPX 300)

### Fixed

* When selecting a machine that has a tab menu in it's properties panel for the first time in a session, the tab menu is now displayed correctly

## Version 2209.2.1 - 2022-11-23

### Fixed

* Saving files containing a PAQTEQ C-250 no longer fails
* The position of the handling table in the DRILLTEQ C series is now correct
* The DRILLTEQ C-100 can now be selected in the 2D & 3D view

## Version 2209.2.2 - 2022-11-29

### Changed

* Restructured machine database in preparation for user management
* Removed 30 day trial

### Fixed

* The material of the mirrors of the DRILLTEQ D-510 is no longer missing
* The material in the CENTATEQ S-900 is no longer missing

## Version 2209.2.3 - 2022-12-01

### Added

* There is now a loading indicator while the machine database is loading

### Fixed

* Hierarchy is now always preserved when loading a save file while the machine database has not yet finished loading
* Markups can once again be used
* The button for resetting all filters in the library panel once again works
* The order of the categories in the libarary panel is now always correct

## Version 2209.3 - 2022-12-15

### Added

* New machine Robot (Universal)
* New machine: Alignmentstation inclined
* New machine: Alignmentstation roller conveyor
* New machine: RKS 300 Shelf
* DRILLTEQ Shelf-Trolley customization to Trolley (Universal)

### Changed

* Replaced the glue feed in the PAQTEQ F-200
* Disabled deprecated robots in library

### Fixed

* The size of the volume scanner is now correct
* The trays in the drawer handling now adjust to the size of the machine
* The load of the Trolley (Universal) is no longer invisible when _Trolley 1_ is selected
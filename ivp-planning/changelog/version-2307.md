# Version 2307

## Version 2307.0
_2023-07-05_

### Added

* New screenshot tool for 2D/3D view
* New video export panel (File > Video Export)
* Added box selection for 3D view
* Added file type association for .plan and .hfc files
* Option to customize color with a color picker for the following machines
    * Roller Conveyor T1
    * Roller Conveyor T1 - Curve
    * Geometric Body
* In context menus and tooltips for actions that also have a keyboard shortcut, the shortcut is now displayed
* Added keyboard shortcut for placing markups (M)

### Changed

* DXF import/export is now available for everyone
* When both machine(s) and folder(s) are selected, only the machines sizes/positions are considered for the selection rect of the 2D view
* When both machine(s) and folder(s) are copied, only the machines sizes/positions are considered for the paste position
* The position handle in the 2D view is now slightly darker, so it has better visibility on white machines
* When creating a folder from the current selection, the folder is now placed at the center of the selection

### Fixed

* When moving machines in the hierarchy, the tooltip now correctly shows the machines name
* Various minor bugfixes

## Version 2307.0.1
_2023-07-12_

### Fixed

* Image import once again works
* Using the photo mode no longer makes the environment invisible after the photo mode is exited under certain conditions
* The position of the terminal in the CABTEQ T-250 is now correct

## Version 2307.1
_2023-08-16_

### Added

* New machines for users:
    * DRILLTEQ H-330 (BHX 330)
    * Infeed Stations (Einlagerplätze)
    * PAQTEQ S-250 (VKV 500)
    * PAQTEQ F-250 (VKF 500)
* New machine for testers:
    * STORETEQ F-100 (TLF 100)
    * SAWTEQ S-300 flexTec (new customizations)
* Tiling customization for imported images

### Changed

* Set default width of Roller conveyor (TFR 561) to 1200mm
* Set default working height of SORTEQ H-200 to 1000mm

### Fixed

* The application now launches faster
* When the application looses focus during startup, it once again continues loading

# Version 2401

## Version 2401.0
_2024-01-18_

### Added

* Support for nested plan files: when importing plan files they now behave like any other file format. You can configure whether they will be included in your current plan file. When they are not included, changes to the original file reflect in your file aswell. Imported plan files can be unpacked, to allow modifying the objects inside.
* It is now possible to enter mathematical expressions into input fields for positions and rotations. You could enter e.g. `1000 + 500` to move an object relative to it's position, but also more complex things such as `2 * (500 + 700)`
* You can now set a layer for each object in it's properties panel. You can define which layers are currently visible in the layer dropdown in the top right.
* The path tool now has a new type _Ground Marking_ with customizable line width, gap, alignment and color.
* It is now possible to switch through the input elements in the properties panel by pressing _tab_ (forwards) or _shift + tab_ (backwards).
* Added the following new machines
    * STORETEQ F-100
    * WALLTEQ M-300
    * CENTATEQ P-110 (PC87)

### Changed

* All objects from the library are now downloaded and updated from Azure
* Objects that are locked can no longer be modified in the properties panel
* The UI in the properties panel now expands to the full width of the panel
* Loading files in the legacy format (.hfc) is no longer supported
* Added Automatic & Semi Automatic Destacking Variants to SAWTEQ S-300 flexTec
* Updated In/Outfeed for Advanced/Premium of DRILLTEQ H-330
* Added options _2 Rolls Magacine_ and a _Length 80_ to EDGETEQ S-380

### Fixed

* When viewing paths perspective mode from the top view of the 3D panel, their lines are no longer sometimes missing parts
* When duplicating markups, their messages now get duplicated aswell

## Version 2401.0.1
_2024-01-19_

### Fixed

* Sign In works again
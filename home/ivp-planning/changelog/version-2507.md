---
title: Version 2507
description: Changelog of version 2507
---

{% embed url="https://vimeo.com/1125436707" %}
iVP Planning Feature Spotlight 2507
{% endembed %}

## Version 2507.1
_2025-07-29_

### Added

- New machine: CENTATEQ N-210 (BHN215)
- New machine: EDGETEQ S-200
- New machine: SAWTEQ S-280 flexTec CN
- New machine: SAWTEQ S-200 flexTec
- New machine: EDGETEQ P-200
- New asset: Cardboard box (universal)
- New asset: Turning belt (MTD 100)
- New asset: Power Line Transport
- New asset: Labelling system (universal)
- New asset: Workpiece (universal)
- Machine update: CENTATEQ P-210 (24-fold tool changer)
- Machine update: CENTATEQ P-100 (CE version, 5-axis machine)
- Machine update: DRILLTEQ H-230 (CE version)
- Machine update: DRILLTEQ H-610 (footprint) for some users

### Fixed

- Imported locked objects are now visible in the video-tool's preview window.
- Rotated objects can now be moved along the world axis inside the 2D View.
- Rotated objects don't change their position after scaling inside the 2D View.


## Version 2507.2
_2025-08-06_

### Added

- New asset: Nest (universal)
- Asset update: Cardboard box (universal) (default size and labels, max. thickness to 7mm)
- Asset update: Labelling system (axes movement possible)
- Asset update: Workpiece (universal) (default size updated)
- Machine update: SORTEQ R-200 and SORTEQ H-600 (tranpsort adjustments)
- Machine update: STORETEQ P-X00 (custom height for 2nd level)

### Changed

- 3D Rotation inside the 3D View is now available for all objects.

{% hint style="warning" %}
__Please note:__ Rotating objects can cause distortions for the projected image in the 2D View (2D-Ansicht). 
{% endhint %}

- The position of selected virtual cameras can be changed by a combination of holding the right mouse button while using the WASD-controls on the keyboard inside the corresponding panel.

{% hint style="warning" %}
__Please note:__ Currently available only for the 3D View (3D-Ansicht). The preview of the Video Tool will follow soon.
{% endhint %}

- There is a new Cloud Panel for uploads of plan files to the iVP Cloud.
- The localizations are detached from the built software and will be updated via the iVP Cloud.

### Fixed

- Path labels are not visible through objects anymore.
- Sub-elements of machines use only the local space if moved.
- Text Objects display properly in 2D view.
- Deprecated PDF-options are removed from the menu. Still they are backwards compatible and will show if you load an old file.
- Path points do not reset anymore when their position is changed via the Properties Panel.
- Some logics of the 2D View have been updated.


## Version 2507.3
_2025-08-14_

### Added

- Asset update: Load Carrier (universal) (New customizations: Seed & Length-Width-Ratio)
- Asset update: Belt Conveyor (TFB 300) can now be mirrored
- New Feature: Colorize feature added for 3D objects.

### Changed

- The calculation of distances between more than one Load Carrier (universal) now takes the sizes of the loaded goods into account, not only the sizees of the carriers.
- Files containing previews versions of the Load Carrier (universal) will be automatically converted according to the logic above.

### Fixed

- Behaviour of overhead textures in the 2D View has been optimized - especially in combination with rotation, scale and PDF files.


## Version 2507.4
_2025-09-02_

### Added

- New machine: STORETEQ H-100
- New asset: Roller Conveyor (TFR 561)
- New asset: Strap Conveyor (TFZ 531)
- New asset: Angle Transfer (TFW 510)
- New feature: Drag & Drop for cameras inside the camera list of the video tool is now possible.
- Machine update: FRAMETEQ F-500 (Accessories/Additional modules).
- Machine update: FRAMETEQ F-700 (Accessories/Additional modules).
- Machine update: BEAMTEQ B-660.
- Asset update: Line switch (TFZ 531) now behaves correctly when its values change.
- Asset update: Line switch (TFZ 531) now behaves correctly when its values change.
- Asset update: Cardboard Box (universal) (0410 and 0429 updated).
- Asset update: Load Carrier (universal) (random values can be locked/unlocked)
- Asset update: Nest (universal)
- Asset update: Power Line Transport
- Asset update: Workpiece (universal)
- Asset update: Turning Belt (MTD 100)
- Asset update: Carcase errector (MTA 200)
- Feature update: 3D colorization has been improved.

### Fixed

- Machine names and model numbers will be mirrored and scaled correctly when using horizontal/vertical mirroring of objects.
- Certain models were not clickable.


## Version 2507.5
_2025-10-08_

### Fixed

- 3D Colorization settings have been improved.
- 2D View texture overlays have been improved.
---
title: Version 2606
description: Changelog of version 2606
---

## Version 2606.1
_2026-06-15_

### New Features

- Performance update and "offline-first" startup
- Concepts: Fully build Maschine files that can be unpacked to change each part

### Feature Updates

- Path tool
    - Add Railings Option
    - Fix corners on Buildings

### General Bugfixes

- DXF export does not ignore small imported DXF files anymore
- PDF export stabilized to display all machines correctly
- Fix machines with size interval change their position on changing size in 2D View
- Fix Path Tool duplicates changing orientation when part of a mirrored folder
- Fix working height not set correctly on machines with different working heights (angles) on loading the Maschine from a save file
- Fix issues with exporting machines to pdf sometimes missing some machines
- Fix .GLB file import
- Seperate import settings of 3D Models and .DXF files

### Machine & Asset Updates

#### Bugfixes

- 3D-Volume-Scanner
    - Fix working height not changing correctly
- Belt conveyor (TFB300)
    - Fix issues on size change not updating belt model
- CENTATEQ N-300 Pro
    - Save Position of Subelements
- EDGETEQ S-500
    - Fix material pad size reset after saving and loading
- Geometric Body
    - Fix issues with bounding box not updating correctly
    - Fix issues with 2D View not showing correct heights
    - Fix issues with geometric bodies not loading correctly when part of a folder
- Load carrier (Universal)
    - Fix panel options not updating correctly in some cases
- Measure station
    - Fix issue with duplicating properties list
- SAWTEQ S-400
    - Air cushion table: Fix artefact on 2810x800 air cushion table size
- Stack (Universal)
    - Fix some objects overhanging in some edge cases
- STORETEQ P-X00 (TLF-X12)
    - Fix issues with pillars not saving/loading and duplicating correctly on certain Maschine widths
- Strap Conveyor (TFZ531)
    - Fix issues with working height when using the Ascent setting with two working heights
- Waste cutter (HRZ)
    - Fix box customization

#### Additions

- Dowel Insertion
    - updated the model
- DRILLTEQ L-200 (ABL110/ABL210/ABL220)
    - added working height customization
- EDGETEQ P-200
    - removed
- PAQTEQ F-250 (VKF500) & PAQTEQ S-250 (VKV500)
    - added glue units customization
- PAQTEQ F-200 (VKF100)
    - changed door position
- SAWTEQ S-200 flexTec
    - Add ground level destacking
- SAWTEQ S-300 flexTec
    - Add ground level destacking
- SAWTEQ S-320 flexTec
    - Add fence customization
    - Add control cabinet customization
- Steel frame two-level storage system
    - Increase height of safety railing from 55 cm to 100cm
- Turning belt (MTD100)
    - Add working height correction and base animation
- Angle transfer (TFW510)
    - Add option to change working height

### New Machines
_(currently for special groups only)_

- BUILDTEQ A-200
- Igelpuffer V-200 (TPI210)
- Igelpuffer V-200 (TPI201)
- PAQTEQ F-200
- PAQTEQ S-200
- SAWTEQ S-65
- SAWTEQ S-190
- Pallett magazine (TPP200)

### New Concepts

- PAQBOT S-300
- PAQBOT S-200\_zero edge R
- PAQBOT S-200\_zero edge L
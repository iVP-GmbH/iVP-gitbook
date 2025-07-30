# Version 2111

![](../../.gitbook/assets/210923\_B320\_v2\_01\_white.jpg)

​

## Version 2111.2 <a href="#version-2111.1-2021-11-12" id="version-2111.1-2021-11-12"></a>
_2021-12-17_

### Added <a href="#added" id="added"></a>

* SAWTEQ B-320 FlexTec (new incl. customization)
* EDGETEQ T-100
* EDGETEQ T-200
* EDGETEQ XES-200
* Smart Hardware Set
* HOMAG Cube PC
* Drucker
* Tablet
* Vertikale Plattenaufteilsäge
* Messstation (new incl. customization)
* Waste Removal (Chinese Market only)

### Updated <a href="#changed" id="changed"></a>

* CABTEQ S-200 (3 customization updates)
* CABTEQ S-250 (47 customization updates)
* PAQTEC C-250 (13 customization updates)
* All SPRAYTEQ (End of life / EOL 31.12.21)
* All MOULDTEQ (End of life / EOL 31.12.21)
* All SANDTEQ (End of life / EOL 31.12.21)
* Schleifbandregal
* Kantenbandregal
* Sortierregal

### Fixed <a href="#fixed" id="fixed"></a>

* Performance Optimization on Trolleys



![](<../../../.gitbook/assets/2111.1 (1).png>)

## Version 2111.1
_2021-11-12_

### Added

* Wood panel material option to rooms created with path tool

### Changed

* Renamed _Halle_ to _Halle Massivholz_
* Improved visual appearance of _Halle Massivholz_
* Legacy versions of the DRILLTEQ L-200 are now hidden in the machine database

### Fixed

* Area measurements are off by factor 1000
* DRILLTEQ L-200 roller conveyors are not always visible
* The following machines are not correctly scaled: CABTEQ T-200, CABTEQ T-250, MTA-200, MTH-150 & MTH-100
* Duplicating a room created with the path tool that has ceiling or floor enabled results in a room with two ceilings/floors

## 2111.0
_2021-11-05_

### Added

* VR support for HTC Vive
* New models
  * Beschlagsetztechnik with following options
    * Magazine Type: Vibratory feeder small / Vibratory feeder medium 1 / Vibratory feeder medium 2 / Vibratory feed large / Drawer handling
    * Platform: On / Off
    * Trays (Drawer handling): 4-8
  * Cabinets with following options
    * Industry: Kitchen / Office
    * Type: Base cabinet / Wall cabinet / Tall cabinet / Container
    * Front: Open / Door / Drawer / Shutter / Sliding Door
    * Version: Assembled / Front / Packed
    * Size: Standard / Wide
  * Drawers with following options
    * Width: S / M / L
    * Height: XS / S / M / L
    * Front: On / Off
  * DRILLTEQ L-200
    * Base machine: ABL110 / ABL210 / ABL 220
    * Workpiece Length: 1300x800mm / 2500x800mm / 3000x800mm / 3000x1300mm
    * Equipment: Drilling / Drilling + Milling
    * Transport Sections: On / Off
    * Infeed & Outfeed: On / Off
    * Configurations: VKNR. 0060 / VKNR. 0061 / VKNR. 0930 / VKNR. 0933 / VKNR. 0934 / VKNR. 0935
  * Durchlaufscanner with following options
    * Scanner 1 / 2 / 3
    * Width (in mm) 1200 / 1400 / 1600 / 1800 / 2000 / 2700 / 3200
  * Halle with the following options
    * Width (free)
    * Length (free)
    * Roof (On / Off)
  * Lastkraftwagen
  * Pre-Assembly (Cabinet) with following options
    * Type: Wall unit - holding flap / Body side tall cabinet with drawer / Carcase bottom with furniture foot adapter / Body side base cabinet with drawer
  * Steig- und Knickbandförderer with following options
    * Version: Ascending conveyor / Articulated belt conveyor
    * Size (for Ascending conveyor): 1300x500 / 1300x800
  * Vakuumpumpen with following options
    * Vacuum Output (in m³/h): 63 / 126 / 189 / 290 / 580 / 870
    * Pumprack: On / Off

### Changed

* Rail length of Querschiebewagen (THS-100) is now customizable
* Updated Ladungsträger (Universal) customization property wording

### Fixed

* Ladungsträger (Universal) places storage goods on wrong positions when rotated
* Wrong translations in General database
* Parts of the following machines do not update correctly when customized:
  * FRAMETEQ F-500
  * FRAMETEQ F-700
  * FRAMETEQ M-500
* Text Object not visible in exported PDF
* Querschiebewagen (THS-100) changes position when resized in 2D-view
* Missing material on mirror of Sawteq B-300 Robin (HPL 300)
* Roboter mit Linearachse is displayed in the 3D-View instead of the preview panel while placing
* Various minor bugs

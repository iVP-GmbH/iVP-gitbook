# Beta

## 2102 - 2021-02-23

### **New Tools**

* New 3D assets: Weinmann &#x20;
* New 3D assets: CNC (currently still work in progress)&#x20;
* Video Export (Rev. 0.1 beta)&#x20;
* Path Tool (Rev. 1)&#x20;
* New User Interface&#x20;

### **Added**&#x20;

* Beamteq B-660, Buildteq&#x20;
* A-570 (WTZ-120)&#x20;
* Buildteq F-500 (WTD)&#x20;
* Feedteq H-300&#x20;
* Frameteq F-500 &#x20;
* Frameteq F-700&#x20;
* Frameteq M-300&#x20;
* Frameteq M-500&#x20;
* Moveteq P-500 (WTW 120)&#x20;
* Moveteq T-500 (WTW ZW)&#x20;
* Moveteq W-100 (WTW 060)&#x20;
* Stockteq D-300&#x20;
* Stockteq U-530&#x20;
* Stockteq V-300&#x20;
* Storeteq H-300&#x20;
* Storeteq H-700&#x20;
* Wallteq M-120&#x20;
* Wallteq M-340&#x20;
* Wallteq M-310 insufill&#x20;
* Holzstück&#x20;
* Geometrischer Körper&#x20;
* Kurve (TFB-261) Statisch&#x20;
* CENTATEQ N-500 Customizable – WIP)&#x20;
* CENTATEQ P-110 (Customizable)&#x20;
* CENTATEQ P-210 (Customizable)&#x20;
* CENTATEQ P-310 (Customizable – WIP)&#x20;
* CENTATEQ S-800 (Customizable)&#x20;
* CENTATEQ S-900 (Customizable)&#x20;
* CENTATEQ T-300 (Customizable)&#x20;
* DRILLTEQ C-300 (Customizable –WIP)&#x20;
* DRILLTEQ D-510 (ABD260) (Customizable)&#x20;
* DRILLTEQ L-200 (ABL XX\_YY) (Customizable –WIP)&#x20;
* DRILLTEQ L-500 (ABL XX\_YY\_B\_F) (Customizable – WIP)&#x20;
* DRILLTEQ L-800 (Customizable – WIP)&#x20;
* DRILLTEQ V-500 (BHX) (Customizable – WIP)&#x20;

### **Miscellaneous**

* Performance optimizations
* Display mouse coordinates and grid origin(View > Coordinate System)&#x20;
* Ability to choose a custom coordinate origin (via the floor plan tab)&#x20;
* New customization option for Stackteq G-500/Loopteq C-500: Arch&#x20;
* New customization option for Winkelübergabe: layers&#x20;
* New customization option for Storeteq S-TLF: outer stands can be moved&#x20;
* The following settings are now persistent across sessions:&#x20;
* Grid on/off (Key G)&#x20;
* Machine animations on/off globally&#x20;
* PDF visible/invisible&#x20;
* Measurements visible/invisible&#x20;
* Overhead View on/off&#x20;
* Walls visible/invisible&#x20;
* Ceiling visible/invisible&#x20;
* InfoPanel visible/invisible&#x20;
* Snapping distance&#x20;
* Language&#x20;
* Custom coordinate origin&#x20;
* Selected options in the save and load dialogue windows&#x20;
* Ability to delete a PDF ground plan &#x20;
* Multi-Copy (In the machine tab)&#x20;
* Naming of machine width has been unified&#x20;
* Bugfixes and improvements

### Known Issues

* 2D Path selection above machine. Selecting a Path icon while it´s over or covered by a machine in 2D view will only select the machine not the path. If you’d like to select the path in this version, please select it in the Path Tab Window or hide (h) the machine for that time.&#x20;
* Video Tool Previous/Next cue. Has currently no effect while not running the timeline. &#x20;
* Camera + F. If you select a virtual camera and press F to find the camera position in the 2D/3D and Hierarchy tab the position of the camera in the 3D view is too low.&#x20;
* Path + F. It´s not possible currently to select a path/fence/room and press F to navigate to the selected path.&#x20;
* From time to time it can happen, that you automatically “multi select” multiple machines in the left machine list window. We know that this issue already, but it is indeed not that easy to fix as it is a bug in the ui framework we use since day 1. The temp solution is, to drag the “width” align (horizontal size of the machine list tab) slider of the machine list tab and just move it to the left or right for just a few mm than the machines will be de- selected. We are working on this issue.&#x20;

## 1.30 - 2020-11-02

* New machines (Weinmann): Beamteq B-660, Buildteq A-570 (WTZ-120), Buildteq F-500 (WTD), Feedteq H-300, Frameteq F-500, Frameteq F-700, Frameteq M-300, Frameteq M-500, Moveteq P-500 (WTW 120), Moveteq T-500 (WTW ZW), Moveteq W-100 (WTW 060), Stockteq D-300, Stockteq U-530, Stockteq V-300, Storeteq H-300, Storeteq H-700, Wallteq M-120, Wallteq M-340, Wallteq M-310 insufill
* New machines (Homag): Holzstück, Geometrischer Körper, Kurve (TFB-261) Statisch
* Performance optimizations
* Display mouse coordinates and grid origin(View > Coordinate System)
* Ability to choose a custom coordinate origin (via the floor plan tab)
* New customization option for Stackteq G-500/Loopteq C-500: Arch
* New customization option for Winkelübergabe: layers
* New customization option for Storeteq S-TLF: outer stands can be moved
* The following settings are now persistent across sessions:
* Grid on/off
* Display of mousecoordinates
* Machine animations on/off globally
* PDF visible/invisible
* Measurements visible/invisible
* Overhead View on/off
* Walls visible/invisible
* Ceiling visible/invisible
* InfoPanel visible/invisible
* Snapping distance
* Language
* Custom coordinate origin
* Selected options in the save and load dialogue windows
* Ability to delete a PDF ground plan (File > Delete PDF)
* Multi-Copy (In the machine tab)
* Naming of machine width has been unified
* Bugfixes and improvements

## 1.20.2.1 - 2020-06-15

* Bugfixes and improvements

## 1.20.2 - 2020-06-08

* Improved bug reporting:
  * Attached save files are now displayed
  * If the report fails to be sent, the entered text is not deleted anymore
  * Files that are too big to be sent can not be attached anymore
* Bugfixes and improvements

## 1.20.1 - 2020-05-25

* Bugfixes and improvements

## 1.20 - 2020-05-18

* The following machines were made customizable: SORTEQ R-200, Kappautomat mit Steigband, Rollenbahn Diagonal, THR-800, Röllchenförderer, Winkelübergabe
* The following customizable machines were added: THS-100, TFL-100, Schaltschränke, Lichtschranken
* The following static machines were added: MTH-100, MTA-200, Runge, Kettenförderer, Röllchen, Sortbot R-300(RKS200) Regal, Stapelrollenbahn, TDL-310, TDL-510, TDL-510 25 25 12, TPP-100, TPA-600
* Added an animation to H-600
* Revised PAQTEQ C-250 & TLF-212
* Added levels to TFB-100 & TFZ-531
* Swapped X- and Y-Axis to match CAD industry standards
* Added the ability to create folders from current selection via right click menu
* Camera speed (3D-View) is now configurable under Settings > Input manager
* Drastically reduced the application size
* Updated legal notice
* Cleaned up database structure
* Removed obsolete machines and Egger concept
* Bugfixes and improvements

## 1.19.1 - 2020-03-18

* Added the ability to move in the 2D view by holding the left mouse button, touchpad or touchscreen
* New machine Feedteq G-500
* Bugfixes and improvements

## 1.19 - 2020-03-10

* The following machines are now customizable: Cabteq S-250, Kurven-Band, Loopteq O-300, Paqteq C-250, Sorteq H-600, Sorteq V-2XX, Stackteq-GXX Standard, TFB-100, TFZ-531
* The following machines were added: FEEDTEQ L-500, STACKTEQ L-500, TDL-310-10-25, TDL-510-25-25-12, TDL-510-25-25-S, EDGETEQ D-610 (KFL525), EDGETEQ D-610 (KFL526), TENONTEQ D-800 (FPL620), DRILLTEQ D-510 (ABD 210-12-D-F), DRILLTEQ D-510 (ABD 210-12-F), DRILLTEQ H-600 (BHX 500, KONZEPT-A1), DRILLTEQ H-600 (BHX 500, KONZEPT-A3), DRILLTEQ L-200 in diverse variants
* All machines were oriented so that their front points to the user when instantiated. The following list shows machines that were rotated since the last release. Caution! These machines are not oriented correctly anymore when loading old save files! Arbeiter, Arbeitsplatz, Basiskonzept C-300, CENTATEQ E-Series, CENTATEQ P-Series, CENTATEQ T-300, DRILLTEQ C-Series, DRILLTEQ L-500 (ABH 100 (VKNR. 3725/...)), DRILLTEQ L-500 (ABH 100 ohne Messstation), DRILLTEQ L-800 Series, EDGETEQ, S-200 to S-500 Series, Stapelrollenbahn with & without Staplerschlitzen, SAWTEQ B-Series, LOOPTEQ O-Series, STACKTEQ G-XXX Standard, PAQTEC C-250, Plattenaufteilsäge, STORETEQ Hordenwagen, SORTEQ V-2XX, SANDTEQ W-Series
* The Y and Z axes were swapped: Z now points up and Y away from the camera
* Further small bug fixes and improvements were done

## 1.18.1 - 2019-12-06

* fixed: Selection outlines and measurements in the 2D-view have the wrong size when a machine is rescaled in 3D-view.

## 1.18 - 2019-12-05

* This release mainly focuses on Bugfixes, performance improvements and user interface design. Additionally the following features were added
* Tooltips
* Ability to report bugs and give feedback from inside iVP. Go to "Help > Report a Bug" to find out more.
* Display the current filename in the upper right corner. Click it to select the file in the Windows Explorer.
* Right click menu for the machine list and the floor.
* Added customization options to: Robot, Robot with linear axis, Storeteq S-TLF, Sorteq H-200, TFR 561, Protective Fences & Protective Windows
* Known Issue: The machine Bandförderer (TFB-100) has the wrong size in the 2D-view (too big)

## 1.17 - 2019-09-09

* Customizable Machines
* Added to customization Panel to the Default Layout
* Added Options to the HPP300 (Machine Name is SAWTEQ B-300 ROBIN (HPL 300) CUSTOMIZABLE)
* Added Options to the HPP300 Robin (Machine Name is SAWTEQ B-300 ROBIN (HPL 300) CUSTOMIZABLE)
* Added Options to the HPS320 (Machine Name is SAWTEQ B-320 FLEXTEC CUSTOMIZABLE)
* UI Overhaul
* The UI has been divided into windows that can be dragged and repositioned
* The machine List has been completely redesigned and now supports folders, layering and new options for batch selecting
* Quality Settings have been simplified and optimized
* User Experience
* When mirroring machines they are now mirrored on the global axis
* Improved multiselect usability: several machines can now be selected by holding ctrl, no need to activate multiselect before (the functionality of the button stays the same to support devices with touchscreen)
* Duplicating multiple redesigned to match behaviour of duplicating a single machine
* Ability to focus on machines in 3D-view by pressing 'F'
* The machine list now has a search option
* PDF Export
* Exported PDFs now have a white background
* Appending a list of all used the machines used to the export is now optional
* Bugfixes and minor improvements

## 1.16 - 2019-07-31

* A documentation is now avaliable under Settings > Help. In the future there will be a ticket system aswell.
* Keyboard shortcuts can now be custumized under Settings > Input manager.
* 3D navigation: machines can now be selected and changed from the 3D view. The available properties position, rotation and scale can be selected from the buttons on the top left corner of the 3D view. The scaling options is still considered experimental.
* Big changes on databases: The databases for the 3D-models will now be loaded from an external \*.ivp file. This makes it possible to update the databases without having to update the software.
* Networking: A user can now enter a name, go online and create a room. Other users can join available rooms for a team session or to review a plan. A chat is available aswell.
* The application will now always run in windowed mode.
* When creating a new file, a popup window will open, so the user can fill in the project information and the filpath.
* The grid is now limited to the floor plan.
* General bugfixes (e.g. saving graphic settings, broken cursor, pdf changes size automatically etc.).

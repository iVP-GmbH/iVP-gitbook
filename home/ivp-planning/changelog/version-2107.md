# Version 2107

## 2107.0
_2021-07-09_

### Added

* New machines:
  * CABTEQ T-200
  * CABTEQ T-250
  * LOOPTEQ O-200 (TFU-120)
  * LOOPTEQ O-600 (TFU-521)
  * PAQTEQ S-200
  * PAQTEQ F-200
  * STACKBOT Hubtisch
  * Etikettierer
  * Volumen-Messstation
  * Semiautomatische Klebestation
  * Ladungsträger (Universal)
  * Regal (Universal)
  * Kragarmregal (Universal)

### Changed

* Updated all CNC machines' customization localizations
* Applied various minor improvements to models of CNC machines:
  * CENTATEQ N-600 (BHP 300)
  * CENTATEQ S-800 (BMB 800)
  * CENTATEQ S-900 (BMB 900)
  * CENTATEQ P-210 (BMG 210)
  * CENTATEQ P-310 (BMG 310)
  * DRILLTEQ C-500
* Added 1500mm width configuration to PAQTEQ C-250 (VKS 250)&#x20;
* Disabled mirroring for following machines:
  * MOVETEQ W-100 (WTW 060)
  * STOCKTEQ V-300
  * Bandförderer (TFB-100)
* Updated SORTEQ H-600 (TPL 221) preview panel camera position
* Various performance improvements & bugfixes

### Fixed

* FEEDTEQ G-500 (TBP 420) model is not changed properly with various customization values
* Changing length of STOCKTEQ D-300 does not visually update 2D View representation
* Created room floor via path tool is not visible in 2D View
* STORETEQ S-200 (TLF-212) blocks interaction with other machines placed within its bounds
* Accessing Robospray from Schuler database is not possible
* Schmalz Jumbo Flex 2D View bounding box size is incorrect
* MOVETEQ T-500 database naming is 'MOVETEQ T 500'
* 'Translation not Found!' is shown in every iVP Textfield for some users around the world

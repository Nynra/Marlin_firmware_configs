# Marlin Bugfix 2.1.x
This branch contains the config files for the Eaglediksix 3D printer a.k.a. Bert. The Marlin firmware source code can be downloaded [here](https://github.com/MarlinFirmware/Marlin/tree/bugfix-2.1.x).

## Printer specs
- Creality Ender 3 Pro
- Bltouch
- BigTreeTech V1.2 motherboard

## Config changes
- PREHEAT_BEFORE_LEVELING: Bed heats to 50C before homing or meshing Z axis (more accurate mesh leveling)
- Advanced pauzing True
- BLTOUCH
- Z_SAFE_HOMING
- BABYSTEPPING
- GRID_MAX_POINTS_X: Mesh 3x3 (5x5 not used because of glass bed)
- PROBING_MARGIN: Probe margin from 10mm to 20mm
- ENABLE_LEVELING_AFTER_G28
- PROBE_OFFSET_WIZZARD
- Comment out: Z_MIN_PROBE_USES_Z_MIN_ENDSTOP_PIN
- USE_PROBE_FOR_Z_HOMING

## Known issues
- Bed mesh has an offset compared to the true bed (screws up mesh application)

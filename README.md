# Marlin Bugfix 2.1.x
This branch contains the config files for the 'new' Tweehek 3D printer. The Marlin firmware source code can be downloaded [here](https://github.com/MarlinFirmware/Marlin/tree/bugfix-2.1.x).

## Printer specs
- Creality Ender 3 Pro
- Creality V422 motherboard

## Config changes
Most config changes due to progmem shortage aren't really needed but still added for consistency between 2# printer menus
- Custom bootscreen with 2# logo
- Bed heats to 50C before homing or meshing Z axis
- Advanced pauzing False (Due to progmem shortage)
- Slim LCD menus True (Due to progmem shortage)
- EEPROM chitchat False (Due to progmem shortage)
- Disable M503 True (Due to progmem shortage)
- Resume after power loss True
- Manual probing mesh 4x4

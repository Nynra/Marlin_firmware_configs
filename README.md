# Marlin Bugfix 2.1.x
This branch contains the config files for the 'old' Tweehek 3D printer. The Marlin firmware source code can be downloaded [here](https://github.com/MarlinFirmware/Marlin/tree/bugfix-2.1.x).

## Printer specs
- Creality Ender 3 Pro
- Creality V1 motherboard

## Config changes
- Custom bootscreen with 2# logo
- Bed heats to 50C before homing or meshing Z axis
- Advanced pauzing False (Due to progmem shortage)
- Slim LCD menus True (Due to progmem shortage)
- EEPROM chitchat False (Due to progmem shortage)
- Disable M503 True (Due to progmem shortage)
- Resume after power loss True
- Manual probing mesh 4x4

## Known issues
- Printer sometimes wont go into boot mode when firmware is uploaded from a pc. The issue can be circumvented by putting the firmware binary on a small SD card (smaller==better) and booting the printer with the SD mounted

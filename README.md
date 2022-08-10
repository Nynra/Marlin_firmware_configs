# Marlin Bugfix 2.1.x
This branch contains the config files for the Eaglediksix 3D printer a.k.a. Bert. The Marlin firmware source code can be downloaded [here](https://github.com/MarlinFirmware/Marlin/tree/bugfix-2.1.x).

## Printer specs
- Creality Ender 3 Pro
- Bltouch
- BigTreeTech V1.2 motherboard

## Config changes
- Bed heats to 50C before homing or meshing Z axis (more accurate mesh leveling)
- Advanced pauzing True
- Resume after power loss False (not needed deu to stable power)
- Mesh 5x5 (more accurate mesh leveling)
- Probe margin from 10mm to 20mm

## Known issues
- Bed mesh has an offset compared to the true bed (screws up mesh application)

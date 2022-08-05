# Marlin Bugfix 2.1.x
This branch contains the config files for the Eaglediksix 3D printer a.k.a. Bert.

## Printer specs
- Creality Ender 3 Pro
- Bltouch

## Config changes
- Bed heats to 50C before homing or meshing Z axis
- Advanced pauzing True
- Resume after pouwer loss False
- Mesh 5x5

## Known issues
- Bed mesh has an offset compared to the true bed (screws up mesh application)
# Tevo-Little-Monster---Klipper-SKR-mini-e3-v3

Tevo Little Monster 
SKR Mini E3 V3 running Klipper with SFS 2.0 Filament Runout Sensor

After many years of being idle, I decided to relive my old Tevo Little Monster. 
I decided to replace the noisy MKR SBASE v1.3 with an easy-to-find SKR Mini E3 V3 board. Everything else including the extruder and 3dtouch is kept stock.

https://github.com/kizza42/TevoLittleMonster was helpful as a starting point for my config, but I needed to edit some of gcode commands as it no longer works with a newer version of klipper.

SKR Mini E3 V3 Adapter
https://www.thingiverse.com/thing:6523503

Update 18 Apr 2025
- Should produce perfect print now
- Add Filament runout sensor (BIGTREETECH Smart Filament Sensor Break Detection BTT SFS V2.0)

Update 9 Mar 2024

Implemented features
- Homing
- Basic BLTouch Pin up/down
- Moving carriage X Y Z (Still very wrong step per mm)
- Running CAL1
- Doing mesh bed leveling
- Seems to print fine

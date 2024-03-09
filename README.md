# Tevo-Little-Monster---Klipper-SKR-mini-e3-v3

Tevo Little Monster 
SKR Mini E3 V3 running Klipper with SFS 2.0 Filament Runout Sensor

After many years of being idle, I decided to relive my old Tevo Little Monster. 
I decided to replace the noisy MKR SBASE v1.3 with an easy-to-find SKR Mini E3 V3 board. Everything else including the extruder and 3dtouch is kept stock.

https://github.com/kizza42/TevoLittleMonster was helpful as a starting point for my config, but I needed to edit some of gcode commands as it no longer works with a newer version of klipper.

Please note that this is a work in progress as I'm not yet able to print anything out yet. 

SKR Mini E3 V3 Adapter
https://www.thingiverse.com/thing:6523503

Update 9 Mar 2024

Implemented features
- Homing
- Basic BLTouch Pin up/down
- Moving carriage X Y Z (Still very wrong step per mm)
- Running CAL1
- Doing mesh bed leveling
- Seems to print fine

To do
-  Waiting for PEI Sheet so I can continue calibrating
-  - Uncomment filament sensor section
- Test end Gcode
- Add a Beeping sound


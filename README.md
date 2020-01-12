![Mount](images/dummies.jpg)

## Just copy it to microSD. Thats all.
You no need to: use any GCode command, know Marlin, Compile or edit any code, manage printer by computer - you don't need to be interested in all above at all, to be able to use Automatic Bed Leveling. After installing this firmware, you'll be able to configure and proceed with Auto Bed Leveling from Ender's display and rotary encoder - it is perfectly fine, if you'll trigger Auto Bed Leveling procedure manually from Ender's display - you dont need to modify initial GCode sequence in your slicer etc - just select and launch - and it will proceed exactly the same as triggered by GCode command. ABL is ok even once for a day full of many of smaller projects printed. And what is best - you also don't need to change anything with heated bed suspensions and springs - just leave as it is and check if your bed is still horizontal once for a few days wit standard springs and big black knobs - which by the way, are perfect...     
Included within this repository binary file "firmware.bin" is all you need, this is edited (thats how BLtouch is always activated and configured) firmware Marlin 2.0bugfix binary for those, who upgraded Ender 3 with:
- [SKR MINI E3 v1.2](https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3/blob/master/hardware/BTT%20SKR%20MINI%20E3%20V1.2/BTT%20SKR%20MINI%20E3%20V1.2manual.pdf) motherboard, in which BLTouch is plugged INSTEAD of Z-stop (in "Z-stop" socket, not in "probe" socket) 
- [BLtouch v3.1](https://www.antclabs.com) (genuine) mounted with popular 3d printed [mount](https://www.thingiverse.com/thing:3003725) from thingiverse, or my [simplification](https://www.thingiverse.com/thing:4097908) of it.


1.Copy file firmware.bin to microSD card

2.Turn OFF Ender3 and stick card into slot

3.Turn ON Ender3 - it will upgrade firmware by itself, nothing to select or confirm by user

4.Remove microSD card from Ender3 and put it into PC. If file extension is changed by printer from "firmware.bin" to "firmware.cur", it means that this binary file is your CURrent firmware, already uploaded by Ender 3 into its mainboard.

THATS ALL




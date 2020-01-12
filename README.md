## Just copy it to microSD. Thats all. 
Instant firmware Marlin 2.0bugfix binary for those, who upgraded Ender 3 with:
- [SKR MINI E3 v1.2](https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3/blob/master/hardware/BTT%20SKR%20MINI%20E3%20V1.2/BTT%20SKR%20MINI%20E3%20V1.2manual.pdf) motherboard, in which BLTouch is plugged in INSTEAD of Z-stop (in "Z-stop" socket, not in "probe" socket) 
- [BLtouch v3.1](https://www.antclabs.com) (genuine) mounted with popular 3d printed [mount](https://www.thingiverse.com/thing:3003725) from thingiverse, or my [simplification](https://www.thingiverse.com/thing:4097908) of it.


So, you installed SKR MINI E3 v1.2 and after a few weeks of completely silent printing, you are confident enough to resolve socond major E3 minus - hopelessly wavy and unstable heatbed. ORIGINAL BLtouch is just mounted, connected and glowing red very promising.    


1.Copy file firmware.bin to microSD card

2.Turn OFF Ender3 and stick card into slot

3.Turn ON Ender3 - it will upgrade firmware by itself, nothing to select or confirm for user

4.Take microSD and put it into PC, if file extension is changed by printer to firmware.cur, it means that 
this binary file is your CURrent firmware, already uploaded by Ender 3 into its mainboard.

![Mount](Images/mount.jpeg)


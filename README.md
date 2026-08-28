**Files for VLB version are currently not yet available - currently undergoing validation and testing, in preparation for Take 4**

CARDSHARK Tiburon Take 4 - Open Source Cirrus Logic CL-GD543x Based VLB VGA Card

As it says on the package. This VGA card for the VESA Local Bus supports a maximum memory size of 2MB, using traditional multiple-CAS FPM 256Kx16 SOJ memory. EDO is supported on CL-GD5434-J-QC-F (notice the -J) but does not improve performance. 60ns or faster is recommended.
Created using KiCAD 8.0.

Features:
- Four layer PCB with generous stitching vias for maximum possible signal integrity
- Optional dedicated regulator for analog DAC power for further improved picture quality
- 2MB FPM memory with 64-bit data bus for CL-GD5430/5434
- Compatible with CL-GD5430 and CL-GD5434
- Uses a 27C256-compatible UV PROM or EPROM chip for the BIOS
- Features my own hand-drawn artwork on back of board

Release History:
- Tiburon Take 4 (planned public re-release): May this one be bug-free.
- Tiburon Take 3 (internal): FINALLY we have a properly working VLB card... so long as you only use a GD5434 and 2MB of memory. One of the RAS lines got screwed, which gets overridden anyway when a GD5434 is used. Also some really minor bugs (wrong resistor values in a couple spots, easily fixed). At least it sure looks nice assembled.
- Take 2 (internal): Almost worked. Major bugs all over the place. Barely functional.
- 0.1b: Major overhaul. Relaid everything, redid a lot of stuff that was broken and didn't work (if the previous version wasted your money... sorry! I feel like a prize horse's arse for uploading something so broken, as it is!)

Provided under the terms of the MIT License.

As you can see I'm a bit of a neophyte when it comes to this GitHub stuff.
Expect this to change as I become more familiar with the platform.

<img width="1920" height="1080" alt="cardshark_front" src="https://github.com/user-attachments/assets/b92b4fc7-ecd2-4a36-8618-fc9795554f7a" />
<img width="1920" height="1080" alt="cardshark_back" src="https://github.com/user-attachments/assets/1c767aca-e8b6-48c7-bb66-694783f0b99a" />
CARDSHARK Tiburon Take 4 - MIT-Licensed, Open-Source Cirrus Logic CL-GD543x Based VLB VGA Card

As it says on the package. This VGA card for the VESA Local Bus supports a maximum memory size of 2MB, using traditional multiple-CAS FPM 256Kx16 SOJ memory. 70ns or faster memory is recommended, as is a CL-GD5434 chip for the fastest speed and least confusing build.
Created using KiCAD 8.0, updated for 10.0 (a thousand apologies if this breaks your older version!)

Features:
- Four layer PCB with cautiously laid ground pours, and judicious usage of stitching vias
- Dedicated regulator for analog DAC power for further improved picture quality
- 2MB FPM memory with 64-bit data bus for CL-GD5434
- Compatible with CL-GD5430 and CL-GD5434
- Uses a 27C256-compatible UV PROM or EPROM chip for the BIOS
- Supports 40MHz VLB bus on motherboards that can actually handle that
- Features my own hand-drawn artwork on back of board

Release History:
- Tiburon Take 4 (planned public re-release): May this one be bug-free. (release pending)
- Tiburon Take 3 (internal): FINALLY we have a properly working VLB card... so long as you only use a GD5434 and 2MB of memory. One of the RAS lines got screwed, which gets overridden anyway when a GD5434 is used. Also some really minor bugs (wrong resistor values in a couple spots, easily fixed). At least it sure looks nice assembled, and so long as it's given a GD5434 with 2MB, it's a monster (of the good kind).
- Take 2 (internal): Almost worked. Major bugs all over the place. Barely functional.
- 0.1b: Major overhaul. Relaid everything, redid a lot of stuff that was broken and didn't work (if the previous version wasted your money... sorry! I feel like a prize horse's arse for uploading something so broken, as it is!)

Provided under the terms of the MIT License.

As you can see I'm a bit of a neophyte when it comes to this GitHub stuff.
Expect this to change as I become more familiar with the platform.

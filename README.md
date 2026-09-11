<img width="2133" height="1200" alt="cardshark_front" src="https://github.com/user-attachments/assets/4414d157-0933-42cd-9690-fe86197c4253" />
<img width="2133" height="1200" alt="cardshark_back" src="https://github.com/user-attachments/assets/5aca1fa9-3e10-48a6-bed0-2a8e58066867" />
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

Known Issues:
- Hand-soldering that PQFP-208 chip with all those thin little pins is a nightmare, even with hot air
- For v1.1, I will be making the 0.1uF cap packages 0805s to make them less exacting to install
- Image quality isn't 100% perfect on LCD. (Some extremely faint vertical lines, though generally much less pronounced than on extant cards); if this bugs you use a CRT monitor with it, or play with your RetroTINK's timings a bit (I suspect the bars are actually timing-related and not noise at all)
- EDO is ONLY supported on CL-GD5434-J-QC, but even then it does not improve performance at all. *NO* other versions support EDO, so don't waste money ordering EDO SOJ chips

Bill of Materials: (All passive parts are 0805/2012 metric unless otherwise indicated)
- 1x Cirrus Logic CL-GD5430 or CL-GD5434 PQFP-208 chip (watch out for fakes - they're everywhere)
- 1x SOIC-14 (3.9mm x 8.7mm P1.27mm) SN74F260DR or directly compatible part
- At least 2x, but up to 4x 256Kx16 dual-CAS Fast Page Mode (*NOT* EDO) SOJ-40 DRAM memory
- 1x 78M05 5V DPAK regulator (LF50 is compatible)
- 1x 14.318MHz DIP-14 CXO 4-pin through-hole oscillator
- 1x MMBT3904 SOT-23 NPN transistor
- 1x TL431DBZ SOT-23 programmable shunt reference
- 3x 11 ohm @ 100MHz ferrite beads (for RGB signals)
- 3x 100+ ohm @ 100MHz ferrite beads (for power rails)
- 2x 1x2 2.54mm pin headers + jumper caps
- 1x 2x3 1.27mm pin header + jumper caps
- 4x 10pF 25/50v MLCC X5R/X7R ceramic capacitor
- 20x 0.1uF 25/50v MLCC X5R/X7R ceramic capacitor
- 4x 2.2uF 25/50v MLCC X5R/X7R ceramic capacitor
- 6x 10uF 25/50v MLCC X5R/X7R ceramic capacitor
- 1x 5mm 22uF 16V SMD electrolytic capacitor
- 1x 0 ohm SMD resistor (or a short snip of wire)
- 3x 0603(1608 metric) 10 ohm SMD resistors
- 1x 4x0603 33 ohm convex SMD resistor pack
- 2x 0603(1608 metric) 75 ohm SMD resistors
- 1x 4x0603 75 ohm convex SMD resistor pack
- 1x 100 ohm SMD resistor
- 3x 0603(1608 metric) 6.8K SMD resistors
- 2x 4x0603 6.8K ohm convex SMD resistor packs
- 1x 0603(1608 metric) 270-330 ohm SMD resistor, 1% thin film
- 2x 1K SMD resistors
- 1x DIP-28 socket + 27C256 or compatible PROM/EEPROM/flash ROM chip for BIOS + BIOS file (figure that out yourself)

Provided under the terms of the MIT License.

As you can see I'm a bit of a neophyte when it comes to this GitHub stuff.
Expect this to change as I become more familiar with the platform.

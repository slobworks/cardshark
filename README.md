CARDSHARK v0.1 - Open Source Cirrus Logic CL-GD543x Based VLB VGA Card

As it says on the package. This VGA card for the VESA Local Bus supports a maximum memory size of 2MB, using traditional multiple-CAS FPM 256Kx16 SOJ memory. CL-GD5436 can use EDO memory. 60ns or faster is recommended.
Created using KiCAD 8.0.
![front](https://github.com/user-attachments/assets/20c142e0-9d0e-4e36-861a-1f0dde790aed)
![back](https://github.com/user-attachments/assets/4963f239-244d-4b1f-813f-4c99a116335c)
Features:
- Four layer PCB with generous stitching vias for maximum possible signal integrity
- Optional dedicated regulator for analog DAC power for further improved picture quality
- 2MB memory with 64-bit data bus for all variants of CL-GD543x
- Compatible with CL-GD5430, CL-GD5434 and CL-GD5436; CL-GD5440 might be supported but is not known if it works
- Uses 29C010-compatible flash memory for reduced cost; has options to select one of four 32K banks within the large 128K flash memory if you wish to try multiple video BIOSes
- Features my own hand-drawn artwork on back of board

Release History:
- 0.1a: Big bunch of very small fixes, including more hand-soldering friendly footprints for SOIC-8 chips and resistor array, 0805 footprints replacing 0603 footprints, majorly cleaned-up footprint and symbol libraries, and the elimination of a number of previously excluded ERC warnings. Version number on board left unchanged otherwise.
- 0.1: Fixed broken SMD socketed PLCC-32 footprint

Other people's stuff I've used:
- Modified PLCC-32 footprint, original by KiCAD (SchrodingersGat?)

Provided under the terms of the MIT License.

As you can see I'm a bit of a neophyte when it comes to this GitHub stuff.
Expect this to change as I become more familiar with the platform.

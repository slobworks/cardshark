CARDSHARK v0.1 - Open Source Cirrus Logic CL-GD5434 Based ISA VGA Card

As it says on the package. This VGA card for the ISA Bus supports a maximum memory size of 2MB, using traditional multiple-CAS FPM 256Kx16 SOJ memory. EDO is supported by later revisions of the CL-GD5434 (at least J), but does not improve performance. 60ns or faster is recommended.
Created using KiCAD 9.0.

<img width="1403" height="728" alt="bleh" src="https://github.com/user-attachments/assets/75885699-b292-4c0e-a92e-33c654ebc6ee" />
<img width="1403" height="728" alt="bleh_back" src="https://github.com/user-attachments/assets/1bd535e8-04b1-45d0-b211-fd535ca2207d" />


The prototype worked great; this version integrates some fixes that my unreleased prototype needed.

Features:
- Four layer PCB with generous stitching vias for maximum possible signal integrity
- 2MB memory with 64-bit data bus
- Compatible with CL-GD5434
- Uses 29C010-compatible flash memory for reduced cost; has options to select one of four 32K banks within the large 128K flash memory if you wish to try multiple video BIOSes
- Features my own hand-drawn artwork on back of board

Release History:
- Take 1: Uploaded ISA version.

Provided under the terms of the MIT License.

As you can see I'm a bit of a neophyte when it comes to this GitHub stuff.
Expect this to change as I become more familiar with the platform.

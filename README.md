<b>Files for the ISA version are temporarily unavailable until I nail some rather nasty bugs that were identified much later in testing. They will be made available again once I have high confidence in the compatibility and quality of the design.</b>

CARDSHARK v0.1 - Open Source Cirrus Logic CL-GD5434 Based ISA VGA Card

As it says on the package. This VGA card for the ISA Bus supports a maximum memory size of 2MB, using traditional multiple-CAS FPM 256Kx16 SOJ memory. 60ns or faster is recommended.
Created using KiCAD 9.0.

<img width="1403" height="728" alt="bleh" src="https://github.com/user-attachments/assets/75885699-b292-4c0e-a92e-33c654ebc6ee" />
<img width="1403" height="728" alt="bleh_back" src="https://github.com/user-attachments/assets/1bd535e8-04b1-45d0-b211-fd535ca2207d" />


The prototype worked great; this version integrates some fixes that my unreleased prototype needed.

Features:
- Four layer PCB with generous stitching vias for maximum possible signal integrity
- 2MB FPM memory with 64-bit data bus
- Compatible with CL-GD5434
- Uses 27C256-compatible DIP UV PROM or EPROM chips
- Features my own hand-drawn artwork on back of board

You should use FPM type memory with this card. One revision, CL-GD5434-J-QC-F, supports EDO memory but gains no performance from it.

Release History:
- 0.1a1: Uploaded ISA version.

Provided under the terms of the MIT License.

As you can see I'm a bit of a neophyte when it comes to this GitHub stuff.
Expect this to change as I become more familiar with the platform.

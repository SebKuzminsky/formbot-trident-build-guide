# Formbot Trident Build Guide

This document provides some guidance for building a Formbot Voron
Trident kit.

This guide is a community effort based on support from the Voron community
and from Formbot.  It is not an official product of the Voron Design
group or Formbot3d.

Please help us make it better by opening issues or PRs on github.


# Versions of the kit

This guide focuses on one specific version of the Formbot Voron Trident
kit, as sold in November 2024.

If you build a different version, please expand the guide to include
any info or instructions that differ.

<details>
    <summary>"VORON Trident R1 Pro CoreXY 3D Printer Kit with Best Quality Parts" (ordered 2024-11-18)</summary>

Advertised features:
* Tap leveling sensor
* Filament runout detector
* LED chamber illumination
* Nevermore air filter
* PT1000 temperature sensor
* DLC hard-wearing gear
* 3 in, 6 out PCB
* Brass wire brush
* EBB SB2209 CAN (RP2040)
* EBB SB0000 CAN
* Metal movable hinge
* Bakelite isolation column
* HDMI 5" touch screen
* Stealthburner + CW2
* Manta M8P + CB1 motherboard
* Famous MOONS motors
* Premium silicone heating pad with integrated thermal fuse
* High quality double sided magnetic flexible PEI sheet
* Genuine Gates belts
* 440C stainless steel linear guide rails
* Precision machined cast aluminum plate

Differences from mainline Voron Trident:
* Bakelite spacers under the bed instead of M4 thumb nuts
* CAN toolhead board
* Umbilical toolhead wiring instead of cable chains

Noteworthy details:
* Uses standard microswitch XY endstops, not hall effect
</details>


# Tools

* A nice set of metric hex keys, e.g. Wera 950/9 or Wiha 26390.  You need 1.5 mm, 2 mm, 2.5 mm, 3 mm, and 4 mm.
* Phillips screwdriver, P0 size
* Flush cutters
* straight edge or ruler
* machinist's square or 123 blocks (for squaring the frame)
* clamps (for squaring the frame)
* measuring tape (for checking diagonals when squaring the frame)
* Threadlocker
* Isopropyl alcohol
* Grease, super lube is a good alternative, spray white lithium grease is another good option (e.g. <https://www.wd40.com/products/white-lithium-grease/>).


# The build process


## Documentation

These build instructions will reference the following manuals:
- [The Voron Trident Assembly Manual](https://github.com/VoronDesign/Voron-Trident/blob/main/Manual/Assembly_Manual_Trident.pdf)
- [The Stealthburner Assembly Manual](https://github.com/VoronDesign/Voron-Stealthburner/raw/main/Manual/Assembly_Manual_SB.pdf)
- [The Voron Tap Assembly Manual](https://github.com/VoronDesign/Voron-Tap/blob/main/Manual/Assembly_Manual_Tap.pdf)
- [Voron Tap r8 errata](https://github.com/VoronDesign/Voron-Tap/blob/main/Manual/R8_errata.md)


## Build sequence

| Manual               | Pages   | Comment
|----------------------|---------|---
| Voron Trident        | 1-21    | Assemble the frame.  It can be a little difficult to tell the different extrusions apart, the holes (tapped and not) can be a hint.
| Voron Trident        | 22-30   |

# SylVii
PIC12F629/675 based modchip for the Wii!

## Table of Contents
1. [How the chip works](#how-the-chip-works)
2. [Assembling the chip](#assembling-the-chip)
3. [Installation](#installation)
4. [Ordering the PCB](#ordering-the-pcb)
5. [Credits](#credits)

### How the chip works
The SylVii is a classic 5/6 wire modchip designed for the Wii (older drive revisions in particular). This chip allows the ability to play backup and imported games on the console, booting of homebrew, easy upgradability with the use of an IC clip and an appropriate PIC programmer, support for various firmwares designed for the PIC12F629/675 (Wiinja/OpenWii/YAOSM/WiiFree), and to enhance many more features of the console's functionality.

<sup>Only Wii consoles with a drive controller of DMS, D2A or D2B is supported, double check this by disassembling the console prior to ordering the chip.</sup>

Softmodding is another alternative to playing imports and backups on your console if your system is not supported, and is much easier in terms of installation if you don't have the necessary soldering skills.

### Assembling the chip
Building the chip requires basic soldering skills. The following materials is as follows:

- Wii with a drive controller of DMS / D2A / D2B. [(check your model here)](https://www.wiidrives.com/)
- PIC12F629/675-I/SN SOP-8 8-bit microcontroller. [(1)](https://www.lcsc.com/product-detail/Microcontroller-Units-MCUs-MPUs-SOCs_Microchip-Tech-PIC12F629-I-SN_C8226.html) / [(2)](https://www.lcsc.com/product-detail/Microcontroller-Units-MCUs-MPUs-SOCs_Microchip-Tech-PIC12F675-I-SN_C9730.html)
- [6.3V 1uF multilayer ceramic capacitor (0805).](https://www.lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_FH-Guangdong-Fenghua-Advanced-Tech-0603F104M500NT_C42998.html)

### Installation
Follow the installation diagram [here.](https://github.com/m4x10187/sylvii-modchip/blob/main/diagrams/sylvii-diagram-v1.pdf)

### Ordering the PCB
PCB thickness must be 1.2mm thick.

- [JLCPCB](https://jlcpcb.com)
- [PCBWay](https://pcbway.com)

### Credits
Sylveon character is a registered trademark of Pokémon Company. Nintendo can suck my balls, forking is necessary. :D

PCB was designed with the open-source [KiCAD](https://www.kicad.org/) software.

The project is open-source and is licensed by the DWTFYWWI license.

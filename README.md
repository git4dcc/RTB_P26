# RTB_P26
[![Real-time Bus (RTB)](https://img.shields.io/badge/RTB_Project-FF6699)](https://www.rtb4dcc.de)
[![Kicad_Libs](https://img.shields.io/badge/Kicad_Libs-29C7FF)](https://github.com/git4dcc/RTB_SamacSys)
[![Apache License 2.0](https://img.shields.io/badge/license-Apache%20License%202.0-lightgray)](https://www.apache.org/licenses/LICENSE-2.0)

This is a **motor DCC decoder development board** you can plug right into a breadboard. It has all the necessary hardware for a DCC decoder, except for the microcontroller.

<details>
<summary>See also</summary>

- [RTB_D16](/../../../../git4dcc/RTB_D16) (DCC Decoder)

</details>

<details>
<summary>User Guides</summary>

- User Guide - DE (to be done)
- User Guide - EN (to be done)

</details>

<img src=supplemental/images/P26_main.jpg width=800>

# Hardware
My PCB layout uses SMD footprints with mainly 0603 parts. With some experience handsoldering is good to use.

<img src=supplemental/images/P26_connect.jpg>

## PCB
- 2-layer PCB, FR4, 1.6mm
- Dimensions: 42mm x 22mm
- VDD voltage: 3.3V, 50mA (optional 5V using a different LDO)
- 18V max DCC voltage
- Railcom transmitter
- Inrush limiter: TPS22810
- H-Bridge: DRV8231

## Kicad
[Schematic](doc/P26_schematic.pdf) | [Layout](doc/P26_layout.pdf) | [Gerber](gerber/P26_0.zip)

<details>
<summary>Dependency</summary>
<br>

:yellow_circle: Requires my Kicad project library [RTB_SamacSys](/../../../../git4dcc/RTB_SamacSys) in the same directory tree.

</details>

# Images
<img src=supplemental/images/P26_usecase1.jpg width=400> <img src=supplemental/images/P26_usecase2.jpg width=400>

This project is intended for hobby use only and is distributed in accordance with the Apache License 2.0 agreement.

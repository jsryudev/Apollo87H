# Acheron Apollo87H

## Introduction

Apollo is a tenkeyless (TKL) keyboard Printed Circuit Board (PCB) which main feature is the per-key RGB lighting. This particular variant, 87H, features an 87-key layout with Kailh hotswap sockets. Additionally, 87H supports a "default" TKL layout, with a 6.25 units spacebar, no split backspace or right shift, and ANSI-only.

Both Apollo and Athena line of PCBs were designed to be "universal" TKL PCBs, that is, designed to fit a wide variety of custom mechanical keyboards. The compatibility list is being built as more people check and test. See the **Keyboard compatibility** section of this README for the available list.

## Technical information

- Layout size: tenkeykess (TKL)
- Compatible switches: MX-like only, features hotswap sockets
- Lighting: per-key RGB through SK6812 mini-E reverse-mounted diodes, no RGB underglow
- Microcontroller: STM32F072CxT6 (x can be either 8 or B)
- Connector: USB Type C on the top side
- Firmware compatibility: QMK (with VIA support)
- Protection hardware:
  * USB data lines and power rail ESD suppressing
  * USB power overvoltage protection
  * Enclosure grounding pad
  * Overcurrent protection
  * LDO crowbar diode
  * EMI suppression (shielding ferrite bead)
- Current release: pre-release Alpha (has not been prototyped yet)
- Designer: Gondolindrim
- License: Acheron Open-Source Hardware License version 1.3

## Keyboard compatibility

## Known compatibilities

- **Geonworks F1-8X and F1-6X:** confirmed by Geon, who tested the PCB 3D files against the case 3D files. Live hardware testing into a machined case is pending.

### Known incompatibilities

- **ai03 KBD8X MKII**: ai03 open-sourced the PCB files for his KBD8X. Alghtough Apollo's edges do fit inside the original PCB's, its connector is more protruded then the original PCB's.

- **PrismA18**: different layouts on the function row.

## Acknowledgements

- The first prototypes of this PCB were paid for and tested by KeebsForAll, who also intends to make units of this PCB available for purchase.

- Geon, who kindly spent time helping design this PCB to fit his keyboards.

## Copyright notice

This project is released under the Acheron Open-Hardware License V1.3. For the license, please refer to the LICENCE.md file.

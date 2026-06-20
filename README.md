# Desktop CNC Machine

A custom-designed desktop CNC machine built from scratch in Fusion 360. The machine is designed for cutting wood, foam, and other lightweight materials while remaining affordable and easy to build.

## Overview

This project started as a belt-driven CNC but was later redesigned to use leadscrews on all axes for improved accuracy and simpler mechanics.

The machine uses:

* 3 Axis Motion (X, Y, Z)
* Arduino Uno + CNC Shield
* GRBL Firmware
* NEMA 17 Stepper Motors
* T8 Leadscrews
* 2020 Aluminium Extrusion Frame
* 3D Printed Components

## Specifications

| Specification | Value                             |
| ------------- | --------------------------------- |
| Working Area  | ~200mm × 200mm                    |
| Axes          | 3                                 |
| Motion System | T8 Leadscrews                     |
| Guide System  | 8mm Smooth Rods + SCS8UU Bearings |
| Controller    | Arduino Uno                       |
| Firmware      | GRBL                              |
| Frame         | 2020 Aluminium Extrusion          |
| Spindle       | 775 DC Motor                      |

## Features

* Fully custom CAD design
* Modular axis design
* Leadscrew-driven motion
* Aluminium extrusion frame
* 6 Endstop support
* GRBL compatible
* 3D printable components
* Standard off-the-shelf hardware

## Design Process

### Initial Concept

The original design used:

* GT2 Belts
* GT2 Pulleys
* LM8UU Bearings

After modelling the system in Fusion 360, the design was changed to use leadscrews for improved accuracy and simpler assembly.

### Y-Axis

The Y-axis was the first axis designed.

The final version includes:

* Two 8mm smooth rods
* One T8 leadscrew
* SCS8UU bearing blocks
* 2020 aluminium extrusion base

The frame was redesigned to use four aluminium extrusions with custom 3D printed mounting components.

### X-Axis

The X-axis was redesigned to improve strength and simplify assembly.

Changes included:

* Stronger side supports
* 70° angled reinforcement
* Direct Z-axis mounting points
* Improved carriage design

### Z-Axis

The Z-axis was completely redesigned.

Features include:

* Direct mounting to the X-axis carriage
* Dual guide rods
* Leadscrew-driven motion
* Custom spindle clamp

The spindle mount uses a clamping system with screws and includes a bottom support to prevent the spindle from falling through.

## Electronics

### Components

* Arduino Uno
* CNC Shield
* 3× Stepper Drivers
* 3× NEMA 17 Motors
* 6× Endstops
* Spindle Driver
* 775 Spindle Motor
* Emergency Stop Button (planned)
* 12V Power Supply

### Software

Firmware:

* GRBL

Control Software:

* Universal G-Code Sender (UGS)

UGS will be used for:

* Machine control
* Sending G-code
* GRBL configuration
* Testing and calibration

## CAD Improvements

Several improvements were made throughout development:

* Fillets for improved looks
* Standardised component sizes
* Buyable rod and leadscrew lengths
* Organised Fusion component structure
* Motion simulation using joints

## Bill of Materials

| Name | Purpose | Quantity | Total Cost (USD) | Link | Distributor |
|---|---|---|---|---|---|
| t8 leadscrew nut 4pc | connects carriage to leadscrew | 1 | 5.62 | https://www.aliexpress.com/item/1005007188421437.html?aem_p4p_detail=202606010645565259910943250180003872754&pdp_ext_f=%7B"order"%3A"180"%2C"spu_best_type"%3A"price"%2C"eval"%3A"1"%2C"fromPage"%3A"search"%7D&search_p4p_id=202606010645565259910943250180003872754_1 | aliexpress |
| 5pc endstops | stops the carriage from moving too far | 1 | 4.77 | https://www.aliexpress.com/item/1005008178660096.html?pdp_ext_f=%7B"order"%3A"125"%2C"eval"%3A"1"%2C"fromPage"%3A"search"%7D | Aliexpress |
| t8 Leadscrews 250mm | Leadscrews | 2 | 5.91 | https://www.aliexpress.com/item/1005010726899970.html?mp=1&pdp_npi=6%40dis%21EUR%21EUR%205.08%21EUR%204.68%21%21EUR%204.58%21%21%21%400b88ab7917803206163526940e11a2%2112000053328707185%21ct%21IE%212650473942%21%212%210%21 | Aliexpress |
| t8 Leadscrew 100mm | Leadscrew | 1 | 3.70 | https://www.aliexpress.com/item/1005010726899970.html?mp=1&pdp_npi=6%40dis%21EUR%21EUR%203.18%21EUR%202.95%21%21EUR%202.89%21%21%21%400b88ab7917803206163526940e11a2%2112000053328707182%21ct%21IE%212650473942%21%211%210%21 | Aliexpress |
| Leadscrew Clamps | connects the motor to the leadscrews | 1 | 7.93 | https://www.aliexpress.com/item/1005007820393080.html?mp=1&pdp_npi=6%40dis%21EUR%21EUR%206.81%21EUR%206.81%21%21EUR%206.81%21%21%21%400b88ab7917803206163526940e11a2%2112000042324936325%21ct%21IE%212650473942%21%211%210%21 | Aliexpress |
| Linear Bearings | Moves long the smooth rods | 1 | 6.45 | https://www.aliexpress.com/item/1005004108098706.html?mp=1&pdp_npi=6%40dis%21EUR%21EUR%205.54%21EUR%205.37%21%21EUR%205.37%21%21%21%400b5e1a3817803199448123969e1126%2112000028059680070%21ct%21IE%212650473942%21%211%210%21 | Aliexpress |
| 8mm Ball Bearings 10pc | Lets the leadscrews rotate | 1 | 2.11 | https://www.aliexpress.com/item/1005011548989882.html?mp=1&pdp_npi=6%40dis%21EUR%21EUR%201.81%21EUR%201.60%21%21EUR | Aliexpress |

Estimated cost:
**$180 - $210 USD**

## Project Goals

* Design a CNC machine from scratch
* Learn CNC design principles
* Learn motion control systems
* Create a functional desktop CNC
* Successfully cut wood and foam
* Produce simple engraved projects

## Gallery

<img width="1758" height="1654" alt="CNC Machine" src="https://github.com/user-attachments/assets/05b2bf74-63ab-45e9-8d6c-2739327ba176" />
<img width="733" height="633" alt="Screenshot 2026-06-02 144624" src="https://github.com/user-attachments/assets/d7fc8e90-243f-4a7b-aed2-5c2eae3defda" />

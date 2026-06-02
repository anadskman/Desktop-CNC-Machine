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

Main components:

* T8 Leadscrews
* T8 Nuts
* Leadscrew Couplers
* 8mm Smooth Rods
* SCS8UU Bearings
* NEMA 17 Stepper Motors
* Arduino Uno
* CNC Shield
* Stepper Drivers
* Endstops
* 2020 Aluminium Extrusion
* 775 Spindle Motor

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


# EEE3088F - Engineering Design Principles 2024

## Overview
This project involves designing **power** and **sensing** modules for a **maze-solving micromouse robot**. The repository includes:
- **Design documentation**
- **PCB design files (Gerber, BOM, CPL)**
- **Firmware for sensing & power modules**
- **Testing procedures & results**

## 📌 Project Breakdown
- **Processor & Motherboard (Given)** - STM32L476 microcontroller.
- **Power Module** - Provides regulated power, battery charging, voltage monitoring.
- **Sensing Module** - Detects walls (front, left, right) and optimizes power use.

## 🛠️ Design Process
1. **Research & Requirements Analysis** - Component selection, PCB constraints.
2. **Circuit Design & Simulation** - Power efficiency, sensor accuracy.
3. **PCB Layout & Manufacturing** - Signal integrity, JLCPCB compliance.
4. **Firmware Development** - STM32 control for power & sensing.
5. **Testing & Debugging** - Oscilloscope, logic analyzer verification.

## 🔬 Testing & Demonstration
- **Sensing Module** - LED indicators for wall detection, tested on a maze rig.
- **Power Module** - Battery charging, motor control, tested with a power jig.

## 📂 Repository Structure
```
📦 EEE3088F-Engineering-Design-Principles-2024
├── 📁 matlab files/                  
├── 📁 Power Subsystem/              #
├── 📁 sensing Subsystem/            
└── README.md                # This document
```

 |

## 🛠️ Tools & Technologies
- **KiCad** - PCB Design
- **STM32CubeIDE** - Firmware Development
- **JLCPCB** - PCB Manufacturing
- **Oscilloscope & Multimeter** - Testing
- **GitHub** - Version Control

## 📞 Contributors
- **Zolile Zoko** - Power Module
- **Manare Rammutla** - Sensing Module

For issues, open a **GitHub Issue**.

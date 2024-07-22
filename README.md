# CM4 CAN Carrier Board

This repository contains the design files and documentation for the CM4 CAN Carrier Board, created using Altium Designer. This board is designed to interface with the Raspberry Pi Compute Module 4 (CM4) and features dual CAN channels utilizing the MCP25xx series CAN controllers and drivers. The board is powered via a 12V supply and includes three different voltage levels: 12V, 5V, and 3.3V.

![rpi-cm4-CAN-board](https://github.com/user-attachments/assets/978c4839-724d-4982-8ac3-1be8d7ae2fbc)

## Features
- Dual CAN Channels: Implemented using MCP25xx series CAN Controllers and drivers.
- Power Supply:
  - Input Voltage: 12V
  - Output Voltages: 5V, 3.3V
- Designed for Raspberry Compute Module 4.
- Designed with Altium Designer.

## Contents
- "./design_files": Contains all Atlium Designer project files
- "./schematics": Schematics in PDF format
- "./docs": Additional documentation and datasheets

# Getting Started
Prerequisites
- Altium Designer
- Raspberry Pi Compute Module 4
- 12V DC Power Supply

## Installation
1. Clone the repository:
   `git clone https://github.com/timoothee/rpi-cm4-CAN-board.git`
3. Open the project from Altium Desginer:
   - Open Altium Designer
   - File -> Open...
   - Navigate to the "designer_files" directory and open the project files
  
# Software Repository
For the software interface that drives the CM4 CAN Carrier Board, please visit the [CM4 CAN Software Interface](https://github.com/timoothee/CAN-Tester.git) repository. 
This software provides the necessary drivers and user interface to fully utilize the CAN channels and other features of the hardware board.

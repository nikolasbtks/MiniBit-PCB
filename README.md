# MiniBit-PCB

## Description

This project demonstrates a custom 2-layer PCB containing the ESP32-S3-Mini microcontroller. This board can be used for embedded development or IoT applications using multiple peripherals.

## Components

1. Microcontroller: ESP32-S3-Mini
   - 512 KB SRAM and 8 MB Flash
   - 240 MHz clock speed 
   
2. USB Connectivity:
   - USB Type-C for data and power 
   - USBLC6-2SC6 for ESD protection

3. Power Supply: AP2112K-3.3 
   - Voltage regulator for stable 3.3V output
  
4. Headers:
   - JTAG headers for debugging
   - GPIO, I2C, UART headers for external connections

## Disclaimer

This project is currently in **testing phase**. The provided documentation is shared for prototyping and learning purposes. If you choose to manufacture and use the board, please proceed with care, as it has not yet been fully validated.

## Schematic and PCB Design

The board was designed using KiCad. Files from the PCB design can be found in the **hardware** folder for board manufacture. This folder includes:

- PCB Schematic 
- PCB Layout
- Gerber files
- Assembly files

## How to Use

1. Power the board
   - Use a USB Type-C cable to power the board.
   
2. Microcontroller Programming:
   - Use Arduino IDE or any other platform to program the microcontroller.
   - Use a debugger with JTAG headers.

3. Peripheral Access
   - Use the GPIO, I2C and UART headers to connect peripherals.

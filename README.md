# PicoBlaze Spartan-3E LCD Message Display

TThis project demonstrates the use of the PicoBlaze microcontroller on a Spartan-3E FPGA to display a custom message on an LCD screen. The project includes the implementation of a PicoBlaze assembly program and the necessary HDL logic to drive the LCD.


## Requirements
- Spartan 3E Starter Kit (reference : XC3S500E - 4FG320 - speed : -4)
- Xilinx ISE 14.7
- VHDL basics
- KCPSM3 assembler (for PicoBlaze assembly code compilation).

## Overview
PicoBlaze is a compact and efficient 8-bit microcontroller designed by Xilinx. In this project:

A custom message is displayed on the Spartan-3E board's LCD.
The PicoBlaze core is configured to handle the LCD communication and control.
Assembly code is written to send character data and commands to the LCD for message display.


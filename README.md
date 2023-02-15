# M4_CAN_Feather_Carrier_v3

## Board Layout
![alt text](https://github.com/2468shrm/M4_CAN_Feather_Carrier_v3/blob/main/Images/PCB.png?raw=true)

## Changes from V2

The changes from [V2](https://github.com/2468shrm/M4_CAN_Feather_Carrier_v2) of this
board are largely layout/component positioning. The following
are the changes:
- DIO voltage selector jumper changed pin assignments
- All stake headers are moved to the same edge of the board (bottom edge). It still selects between 5V and 3.3V.
- All STEMMA QT/QWIIC connectors are moved to the same edge of the board (right edge).
- Screw terminals for power and NEOPIXEL are replaced with WAGO 250-series connectors. These are the same connectors used in REV products (CAN, low-current power, etc.).
- The board size changed to 64 x 52 mm.
- The mounting holes are consistently 3 mm from their respective edges.
- The orientation of the ICs (level shifter and analog buffer) are in the same orientation.

Other than that, there are minor changes to make assembly simpler.  Primarily this includes
changing the two ICs so that pin 1 is in the same orientation (V2 had pin 1 pointing in
oppposite directions and sometimes one might forget).

A PDF copy of the schematic [here](https://github.com/2468shrm/M4_CAN_Feather_Carrier_v3/blob/main/Images/Schematic.pdf).

## Checkout Status

This board was fabbed at JLCPCB during the week of 30 Jan, 2023 and articles received
(plus solder stencil). One article has been assembled and the following has been tested:
- Power input filter
- 5V supply
- X1 (I2C/STEMMA QR/QWIIC) interface
- NeoPixel interface

Not yet tested:
- X2-X4
- Level shifter and DIO interface
- Analog buffer and AI interface

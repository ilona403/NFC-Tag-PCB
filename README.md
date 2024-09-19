# NFC-Tag-PCB
![image](https://github.com/user-attachments/assets/925689d3-8430-4f02-8f68-e8e9a095671b)

| Component    | Manufacurer Part Number |
| --------     | ------- |
|  White LED    | KT-0603W |
| 68Ω Resistor |   CRCW060368R0FKEAHP  |
| 220nF Capacitor    |  GRM155R71C224KA12D  |
| NFC Chip    | NT3H2111W0FHKH  |
| Antenna    | Custom    |

## Overview
The NFC-Tag PCB is a custom NFC tag that can be programmed and read by NFC tools. Different types of files and links can be programmed written onto the ship, to then by read by a device with NFC reading capacbility. This PCB is on the smaller size, which allows it to be put onto a keychain.  It also lights up it LED whenever it is placed against an NFC reader.

## Antenna Design
The input capacitance of the NTAG chip is 50pF. The equation for the resonant frequency is $\omega = \frac{1}{\sqrt{LC}}$ The input frequency is 13.56 MHz. Thus the inductance of the antenna must be 2.75$\mu$H.

The actual dimensions of the antenna were determined by using the NXP Antenna Design Tool: https://community.nxp.com/t5/NFC/bd-p/nfc
![image](https://github.com/user-attachments/assets/2f156877-f5c2-45ef-a88d-f3d35930b41d)

The constraints were creating a smaller sized loop antenna, but having the inductance of 2.75$\mu$H.



## Schematic Design

## Layout

## Programming the Chip

## Final Product

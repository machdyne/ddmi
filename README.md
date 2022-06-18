# DDMI (Differential Data Multiple Interface)

## Overview

DDMI (Differential Data Multiple Interface) is a work-in-progress (non-)specification for differential data transfer over an HDMI&reg; connector.

This repo contains the pinout for the DDMI connector and the [DDMI Pmod&trade; compatible module](https://machdyne.com/product/ddmi-pmod).

![DDMI Pmod](https://github.com/machdyne/ddmi/blob/5b369be5159b5f61a21ae51bad638b94bcf4372a/ddmi.png)

This project was inspired by [DVI-PMOD](https://github.com/Wren6991/DVI-PMOD), [SmolDVI](https://github.com/Wren6991/SmolDVI) and the [ULX3S](https://github.com/emard/ulx3s) GPDI connector. 

## Devices

The following is a list of devices with DDMI ports:

  * [Schoko](https://machdyne.com/product/schoko-computer)
  * [Bonbon](https://machdyne.com/product/bonbon-computer)

## DDMI Connector Pinout
| Pin | Signal |
| --- | ------ |
| 1 | D2\_P |
| 2 | GND |
| 3 | D2\_N |
| 4 | D1\_P |
| 5 | GND |
| 6 | D1\_N |
| 7 | D0\_P |
| 8 | GND |
| 9 | D0\_N |
| 10 | CK\_P |
| 11 | GND |
| 12 | CK\_N |
| 13 | NC |
| 14 | NC |
| 15 | NC |
| 16 | NC |
| 17 | GND |
| 18 | PWR5V0 |
| 19 | NC |
| SHIELD | GND |

## DDMI PMOD Pinout (V0/V1)

| Pin | Signal |
| --- | ------ |
| 1 | D2\_N |
| 2 | D1\_N |
| 3 | D0\_N |
| 4 | CK\_N |
| 5 | GND |
| 6 | PWR3V3 |
| 7 | D2\_P |
| 8 | D1\_P |
| 9 | D0\_P |
| 10 | CK\_P |
| 11 | GND |
| 12 | PWR3V3 |

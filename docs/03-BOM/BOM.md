# Bill of Materials

## Overview

This bill of materials includes all components required for the servo and OLED control subsystem. Components available from the TECH162 inventory are listed because they are part of the design, but they have a **$0 purchase cost**. The PIC18F57Q43 Curiosity Nano is already owned and also has a $0 additional cost.

The quantities in the **Order Qty.** column include spare components where appropriate. The OLED and servo are reusable off board modules, so only one of each is requested. Prices are in US dollars.
## Purchase Summary

| Vendor | Items to Purchase | Subtotal |
| --- | --- | ---: |
| Amazon | Hosyond 2.42-inch OLED | $15.59 |
| Hitec | HS-485HB servo | $28.99 |
| DigiKey | Three push buttons and two TO-220 heat sinks | $1.97 |
| **Total Before Shipping and Tax** |  | **$46.55** |

## Major Components

| Component | Reference | Required Qty. | Order Qty. | Unit Cost | Order Total | Manufacturer | Part Number | Source / Status |
| --- | --- | ---: | ---: | ---: | ---: | --- | --- | --- |
| PIC18F57Q43 Curiosity Nano | U1 | 1 | 0 | $0.00 | $0.00 | Microchip | DM164150 | Already owned |
| 2.42-inch 128×64 I²C OLED, SSD1309 | J3 | 1 | 1 | $15.59 | $15.59 | Hosyond | ASIN B0G2RFLG1L | [Amazon](https://a.co/d/0i3j9NDr) |
| HS-485HB analog servo | J2 | 1 | 1 | $28.99 | $28.99 | Hitec | 33485S | [Hitec](https://www.hiteccs.com/actuators/product-details/HS-485HB) |
| 5 V, 1.5 A linear regulator, TO-220 | U2, U3 | 2 | 0 | $0.00 | $0.00 | Taejin | LM7805T | TECH162 stock |
| Regulated 9 V, 3 A power supply | Off-board | 1 | 0 | $0.00 | $0.00 | BestCH | 9V3A power supply | TECH162 stock |

## Power Protection, Connectors, and Debug Hardware

| Component | Reference | Required Qty. | Order Qty. | Unit Cost | Order Total | Manufacturer / Part Number | Source / Status |
| --- | --- | ---: | ---: | ---: | ---: | --- | --- |
| PCB-mount barrel jack | J1 | 1 | 0 | $0.00 | $0.00 | Same Sky PJ-102AH | TECH162 stock |
| 2 A, 5×20 mm fuse | F1 | 1 | 0 | $0.00 | $0.00 | Eaton BK1-S500-2-R | TECH162 stock |
| 1.6 A, 5×20 mm fuse | F2 | 1 | 0 | $0.00 | $0.00 | Littelfuse 021701.6MXP | TECH162 stock |
| 0.5 A, 5×20 mm fuse | F4 | 1 | 0 | $0.00 | $0.00 | Schurter 0034.1513 | TECH162 stock |
| PCB fuse holder for 5×20 mm fuse | F1, F2, F4 | 3 | 0 | $0.00 | $0.00 | Keystone 4628 | TECH162 stock |
| 2×4 IDC ribbon-cable header and cable | J4 | 1 set | 0 | $0.00 | $0.00 | 2.54 mm IDC hardware | TECH162 stock |
| Breakaway 1×4 male header | J5 | 1 | 0 | $0.00 | $0.00 | 2.54 mm header strip | TECH162 stock |
| 1×2 jumper header and shunt | JP1 | 1 set | 0 | $0.00 | $0.00 | 2.54 mm header and shunt | TECH162 stock |
| Female headers for Curiosity Nano | U1 | 2 strips | 0 | $0.00 | $0.00 | 2.54 mm female header strips | TECH162 stock |
| SPST-NO through hole tactile switch | SW1 | 1 | 3 | $0.19 | $0.57 | GCT SWT0325-073016TSK | [DigiKey](https://www.digikey.com/en/products/detail/gct/SWT0325-073016TSK/28022330) |
| TO-220 heat sink | Mechanical | 1 | 2 | $0.70 | $1.40 | Assmann WSW V6560W | [DigiKey](https://www.digikey.com/en/products/detail/assmann-wsw-components/V6560W/3511441); one required and one spare |
| PCB test pads | TP1-TP11 | 11 | 0 | $0.00 | $0.00 | Plated test-pad footprints | Made as part of the PCB |

## Passives and Indicators

| Component and Rating | Reference | Qty. | Purchase Cost | Source / Status |
| --- | --- | ---: | ---: | --- |
| 0.33 µF, 50 V capacitor | C1, C5 | 2 | $0.00 | TECH162 capacitor assortment |
| 0.1 µF, 50 V capacitor | C2, C4, C6, C7 | 4 | $0.00 | TECH162 stock |
| 10 µF, 16 V capacitor | C3 | 1 | $0.00 | TECH162 capacitor assortment |
| 470 µF, 16 V electrolytic capacitor | C8 | 1 | $0.00 | TECH162 capacitor assortment |
| 1 µF, 50 V capacitor | C9 | 1 | $0.00 | TECH162 capacitor assortment |
| 220 Ω, 1/4 W resistor | R1 | 1 | $0.00 | TECH162 resistor kit |
| 330 Ω, 1/4 W resistor | R2, R4, R5 | 3 | $0.00 | TECH162 resistor kit |
| 10 kΩ, 1/4 W resistor | R3 | 1 | $0.00 | TECH162 resistor kit |
| Blue LED | D1 | 1 | $0.00 | TECH162 LED assortment |
| Red LED | D2 | 1 | $0.00 | TECH162 LED assortment |
| Yellow LED | D3 | 1 | $0.00 | TECH162 LED assortment |

## Cost Summary

The total cost of components that must be purchased is approximately **$46.55 before shipping and tax**.

The PIC development board is already owned. The regulators, power supply, fuses, fuse holders, connectors, capacitors, resistors, LEDs, headers, ribbon cable hardware, and other general components are available from TECH162 stock and therefore add no purchase cost.

The required purchase requests are:

1. **Amazon**

    - One Hosyond 2.42-inch OLED
    - Subtotal: **$15.59**

2. **Hitec**

    - One Hitec HS-485HB servo
    - Subtotal: **$28.99**

3. **DigiKey**

    - Three through-hole push buttons
    - Two TO-220 heat sinks
    - Subtotal: **$1.97**

# Schematic Bill of Materials

| Reference | Qty | Value | Footprint | Datasheet |
|-----------|-----|-------|-----------|-----------|
| C1, C2 | 2 | 12 pF | SMD_603 | [Yageo X7R](https://yageogroup.com/content/datasheet/asset/file/UPY-GPHC_X7R_6_3V-TO-250V) |
| C3 | 1 | 100 nF | SMD_603 | [Yageo X7R](https://yageogroup.com/content/datasheet/asset/file/UPY-GPHC_X7R_6_3V-TO-250V) |
| C4, C7 | 2 | 100 nF | SMD_603 | [Yageo X7R](https://yageogroup.com/content/datasheet/asset/file/UPY-GPHC_X7R_6_3V-TO-250V) |
| C6 | 1 | 1 µF | SMD_603 | [Yageo X7R](https://yageogroup.com/content/datasheet/asset/file/UPY-GPHC_X7R_6_3V-TO-250V) |
| D1 | 1 | LED Green | SMD_603 | [KP-1608ID](https://cdn-reichelt.de/documents/datenblatt/A500/KP-1608ID(VER.9A).pdf) |
| D2 | 1 | LED Red | SMD_603 | [KP-1608ID](https://cdn-reichelt.de/documents/datenblatt/A500/KP-1608ID(VER.9A).pdf) |
| J1 | 1 | Connector | J1_connector | [Samtec TSW](https://suddendocs.samtec.com/catalog_english/tsw_th.pdf) |
| J2 | 1 | Connector | J2_connector | [Samtec TSW](https://suddendocs.samtec.com/catalog_english/tsw_th.pdf) |
| J3 | 1 | FTDI | TSW-106-08-L-S-RA | [Samtec TSW](https://suddendocs.samtec.com/catalog_english/tsw_th.pdf) |
| R1 | 1 | 330 Ω | SMD_603 | [Yageo RC](https://yageogroup.com/content/datasheet/asset/file/PYU-RC_GROUP_51_ROHS_L) |
| R2, R3 | 2 | 10 kΩ | SMD_603 | [Yageo RC](https://yageogroup.com/content/datasheet/asset/file/PYU-RC_GROUP_51_ROHS_L) |
| SW1 | 1 | Push Switch | B3U-1000P(M) | [Omron B3U](https://omronfs.omron.com/en_US/ecb/products/pdf/en-b3u.pdf) |
| U1 | 1 | ATmega328P-A | TQFP-32 | [Microchip](https://ww1.microchip.com/downloads/aemDocuments/documents/corporate-responsibilty/environmental/material-compliance-documents/32L_TQFP_7x7x1_0mm_PT_C04-00074c.pdf) |
| Y1 | 1 | 16 MHz Crystal | SMD3225-4P | [X322516MLB4SI](https://www.lcsc.com/datasheet/C13738.pdf) |

## Summary

| Category | Count |
|----------|-------|
| Capacitors (C) | 6 |
| Diodes / LEDs (D) | 2 |
| Connectors (J) | 3 |
| Resistors (R) | 3 |
| Switch (SW) | 1 |
| Microcontroller (U) | 1 |
| Crystal (Y) | 1 |
| **Total components** | **17** |



# Pinout — Schematic (ATmega328P-A)

## J1 (12-pin, left connector)

| Pin | Signal |
|-----|--------|
| 12  | TXO    |
| 11  | RXI    |
| 10  | RST    |
| 9   | GND    |
| 8   | D2     |
| 7   | D3     |
| 6   | D4     |
| 5   | D5     |
| 4   | D6     |
| 3   | D7     |
| 2   | D8     |
| 1   | D9     |

---

## J2 (12-pin, right connector)

| Pin | Signal |
|-----|--------|
| 1   | RAW    |
| 2   | GND    |
| 3   | RST    |
| 4   | VCC    |
| 5   | A3     |
| 6   | A2     |
| 7   | A1     |
| 8   | A0     |
| 9   | SCK    |
| 10  | MISO   |
| 11  | MOSI   |
| 12  | D10    |

---

## J3 — FTDI (6-pin)

| Pin | Signal |
|-----|--------|
| 6   | GND    |
| 5   | GND    |
| 4   | VCC    |
| 3   | RXI    |
| 2   | TXO    |
| 1   | DTR    |

Top View Drawings



<img width="824" height="532" alt="Capture d’écran 2026-05-17 à 12 26 42" src="https://github.com/user-attachments/assets/d7fe05e6-f919-4031-b669-b4395d818313" />
<img width="824" height="532" alt="Capture d’écran 2026-05-17 à 12 28 25" src="https://github.com/user-attachments/assets/85a4d709-af7e-4640-9032-f189eb9247fa" />

## Soldered another PCB but even smaller </br>
The atmega328P-au was hard to do, had to resolder it 5 times until placed exactly on the pads.</br>
size of the MCU is 7mm x 7mm and 32 pads </br>
example size of a LED 

Top View Drawings



<img width="583" height="965" alt="carte" src="https://github.com/user-attachments/assets/ea49f76e-7522-4df0-b6d8-70a1da3fbb52" />
<img width="623" height="916" alt="IMG_3976" src="https://github.com/user-attachments/assets/763ced57-e98d-46c7-9626-aa43760376c1" />




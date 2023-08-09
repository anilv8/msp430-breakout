# MSP430 Breakout

Simple reakout bord for MSP430G25553.

# Schematic of circuit
![schematic](https://github.com/anilv8/msp430-breakout/assets/81171588/2c958006-e98f-49eb-aa53-b1609830623e)

## ERC Result
![erc](https://github.com/anilv8/msp430-breakout/assets/81171588/d712105a-a088-495d-b6ec-b7e0a4351998)

# PCB Board
### Front Copper
![pcb-front-copper](https://github.com/anilv8/msp430-breakout/assets/81171588/ab2f2618-28b7-4ca5-a855-e79ed8ed44de)

### Back copper
![pcb-back-copper](https://github.com/anilv8/msp430-breakout/assets/81171588/727c3250-035b-45e0-986f-79a67c11e4eb)

## DRC Result
![drc](https://github.com/anilv8/msp430-breakout/assets/81171588/cb14afaf-27db-4828-a2cf-a6a71d5147a1)

## 3D view of PCB
### Front:
![3d-top](https://github.com/anilv8/msp430-breakout/assets/81171588/c012f19d-26d2-413d-b4b9-8e6e821824ca)

### Back:
![3d-bottom](https://github.com/anilv8/msp430-breakout/assets/81171588/921381e1-62d1-4c4a-9db5-826af749d941)

## Gerber
### Front Copper
![front-copper](https://github.com/anilv8/msp430-breakout/assets/81171588/84393ba7-f542-4c77-97c6-42f850608720)

### Back Copper
![back-copper](https://github.com/anilv8/msp430-breakout/assets/81171588/994641b9-ed9d-44aa-acad-7fad8a3bf1b9)

# BOM
| Item |	Qty |	Reference(s)	| Value	| LibPart |	Footprint |	Datasheet |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 1 |	1	| C1	| 1u	| Device:C |	Capacitor_SMD:C_0603_1608Metric_Pad1.08x0.95mm_HandSolder |	~ |
| 2 |	2	| C2, C3	| 10u	| Device:C	| Capacitor_SMD:C_0603_1608Metric_Pad1.08x0.95mm_HandSolder	| ~ |
| 3 |	1 |	C4	| 10n |	Device:C	| Capacitor_SMD:C_0603_1608Metric_Pad1.08x0.95mm_HandSolder	| ~ |
| 4	| 2	| D1, D2	| LED | Device:LED |	LED_SMD:LED_0603_1608Metric_Pad1.05x0.95mm_HandSolder |	~ |
| 5	| 2	| J1, J2	| Conn_01x10	| Connector_Generic:Conn_01x10	| Connector_PinHeader_2.54mm:PinHeader_1x10_P2.54mm_Vertical |	~ |
| 6	| 1	| J3	| USB_B_Mini	| Connector:USB_B_Mini |	Connector_USB:USB_Mini-B_Wuerth_65100516121_Horizontal |	~ |
| 7	| 2	| R1, R2	| 100	| Device:R	| Resistor_SMD:R_0603_1608Metric_Pad0.98x0.95mm_HandSolder |	~ |
| 8	| 1	| R3	| 47k	| Device:R	| Resistor_SMD:R_0603_1608Metric_Pad0.98x0.95mm_HandSolder	| ~ |
| 9	| 1	| SW1	| SW_Push	| Switch:SW_Push |	Button_Switch_THT:SW_TH_Tactile_Omron_B3F-10xx |	~ |
| 10	| 1	| U1	| MSP430G2553IPW20	| MCU_Texas_MSP430:MSP430G2553IPW20	Package_DIP:DIP-20_W7.62mm_Socket |	http://www.ti.com/lit/ds/symlink/msp430g2553.pdf |
| 11	| 1	| U2	| AMS1117-3.3	| Regulator_Linear:AMS1117-3.3	| Package_TO_SOT_SMD:SOT-223-3_TabPin2 |	http://www.advanced-monolithic.com/pdf/ds1117.pdf |

# REFERENCES
[1]  https://github.com/akowalczyk18/Kicad/tree/master/1-Hour-Board/1-Hour-Board

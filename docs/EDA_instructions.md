# Gremlin APC 710

## EDA Instructions

This document describes the electronics design files and a basic workflow for working with the APC 710 KiCAD project.

## Project Files

- KiCAD project file: [EDA/apc_710.kicad_pro](../EDA/apc_710.kicad_pro)
- Schematic: [EDA/apc_710.kicad_sch](../EDA/apc_710.kicad_sch)
- PCB layout: [EDA/apc_710.kicad_pcb](../EDA/apc_710.kicad_pcb)

## Bill Of Materials

| Qty | Value | Footprint | References |
| --- | --- | --- | --- |
| 2 | Conn_02x13_Odd_Even | Connector_IDC:IDC-Header_2x13_P2.54mm_Vertical | CONN_D0, CONN_D1 |
| 14 | LED | LED_THT:LED_Rectangular_W3.0mm_H2.0mm | D_ALT1, D_AP1, D_APR1, D_BANK1, D_BC1, D_FLC1, D_HDG1, D_NAV1, D_SPD1, D_VNV1, D_VS1, D_XFR_L1, D_XFR_R1, D_YD1 |
| 5 | RotaryEncoder_Switch | easyeda2kicad:SW-TH_PEC11H-4020F-S0016 | RE_ALTS1, RE_CRS1, RE_CRS2, RE_HDG1, RE_UPDN1 |
| 14 | 220Ω | Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | R_ALT1, R_AP1, R_APR1, R_BANK1, R_BC1, R_FLC1, R_HDG1, R_NAV1, R_SPD1, R_VNV1, R_VS1, R_XFR_L1, R_XFR_R1, R_YD1 |
| 14 | SW_Push | Button_Switch_THT:SW_PUSH_6mm_H5mm | SW_ALT1, SW_AP1, SW_APR1, SW_BANK1, SW_BC1, SW_FD1, SW_FLC1, SW_HDG1, SW_NAV1, SW_SPD1, SW_VNV1, SW_VS1, SW_XFR1, SW_YD1 |

## Assembly

All components are through hole and can be soldered with hobby-grade equipment. Note that the IDC-Header_2x13_P2.54mm_Vertical connectors can be replaced by your choice of 2.54 mm pitch headers. The LED_Rectangular_W3.0mm_H2.0mm can be up to 6 mm in height, 4 mm is recommended. The SW-TH_PEC11H-4020F-S0016 are Bourns PEC11H-4020F-S0016 but generic equivalents can be easily sourced as EC11 D-shaft switch encoders.
# Atomic_ migration — 2026-11-12

What this migration moved or renamed, and how to relink an existing KiCad project.

## Libraries
- Atomic_Oscillator -> Atomic_Oscillator
- Connector_FFC_GCT -> Atomic_Connector
- Connector_MicroSD_GCT -> Atomic_Connector
- Connector_USB_GCT -> Atomic_Connector
- IC_Battery_Charger_TI -> Atomic_Battery_Management
- IC_Battery_Fuel_Gauge_ADI -> Atomic_Battery_Management
- IC_Battery_Management_TI -> Atomic_Battery_Management
- IC_Button_Controller_ADI -> Atomic_Power_Management
- IC_IMU_TDK -> Atomic_Sensor_Motion
- IC_Magnetometer_Memsic -> Atomic_Sensor_Magnetic
- IC_PowerManagementMosfet_TI -> Atomic_Transistor_FET
- IC_Wireless_BLE_uBlox -> Atomic_RF_Module
- LED_Cree -> Atomic_LED
- RECOM_DCDC_converters -> Atomic_Converter_DCDC_Isolated

## Symbols
- Atomic_Oscillator:CM315D32768DZFT -> Atomic_Oscillator:CM315D32768DZFT
- Connector_FFC_GCT:FFC2A32-06-T -> Atomic_Connector:FFC2A32-06-T
- Connector_MicroSD_GCT:MEM2085-00-115-00-A_REV0.2 -> Atomic_Connector:MEM2085-00-115-00-A
- Connector_USB_GCT:USB4056-03-A_REVA2 -> Atomic_Connector:USB4056-03-A
- Connector_USB_GCT:USB4730-GF-A_REVA -> Atomic_Connector:USB4730-GF-A
- Connector_USB_GCT:USB4745-03-A_REVA -> Atomic_Connector:USB4745-03-A
- IC_Battery_Charger_TI:BQ25180YBGR -> Atomic_Battery_Management:BQ25180YBGR
- IC_Battery_Fuel_Gauge_ADI:MAX17048G -> Atomic_Battery_Management:MAX17048G
- IC_Battery_Fuel_Gauge_ADI:MAX17048X -> Atomic_Battery_Management:MAX17048X
- IC_Battery_Management_TI:BQ29700 -> Atomic_Battery_Management:BQ29700
- IC_Button_Controller_ADI:LTC2954-1-DFN8 -> Atomic_Power_Management:LTC2954IDDB-1
- IC_Button_Controller_ADI:LTC2954-1-TSOT-23 -> Atomic_Power_Management:LTC2954ITS8-1
- IC_Button_Controller_ADI:LTC2954-2-DFN8 -> Atomic_Power_Management:LTC2954IDDB-2
- IC_Button_Controller_ADI:LTC2954-2-TSOT-23 -> Atomic_Power_Management:LTC2954ITS8-2
- IC_IMU_TDK:ICM-42688-P -> Atomic_Sensor_Motion:ICM-42688-P
- IC_Magnetometer_Memsic:MMC5983MA -> Atomic_Sensor_Magnetic:MMC5983MA
- IC_PowerManagementMosfet_TI:CSD85301Q2 -> Atomic_Transistor_FET:CSD85301Q2
- IC_Wireless_BLE_uBlox:NORA-W106-00B -> Atomic_RF_Module:NORA-W106-00B
- IC_Wireless_BLE_uBlox:NORA-W106-10B -> Atomic_RF_Module:NORA-W106-10B
- LED_Cree:UHD1110-FKA-CL1A13R3Q1BBQFMF3 -> Atomic_LED:UHD1110-FKA-CL1A13R3Q1BBQFMF3
- RECOM_DCDC_converters:RS3-1212S_H3 -> Atomic_Converter_DCDC_Isolated:RS3-1212S_H3

## Footprint links
- Connector_FFC_GCT:GCT_FFC2A32-06-T -> Atomic_Footprints:GCT_FFC2A32-06-T
- Connector_MicroSD_GCT:GCT_MEM2085-00-115-00-A_REV0.2 -> Atomic_Footprints:GCT_MEM2085-00-115-00-A_REV0.2
- Connector_USB_GCT:GCT_USB4056-03-A_REVA2 -> Atomic_Footprints:GCT_USB4056-03-A_REVA2
- Connector_USB_GCT:GCT_USB4730-GF-A_REVA -> Atomic_Footprints:GCT_USB4730-GF-A_REVA
- Connector_USB_GCT:GCT_USB4745-03-A_REVA -> Atomic_Footprints:GCT_USB4745-03-A_REVA
- IC_Battery_Charger_TI:IC_BQ25180YBGR -> Atomic_Footprints:IC_BQ25180YBGR
- IC_Battery_Fuel_Gauge_ADI:BGA8N40P2X4_93X167X69N -> Atomic_Footprints:BGA8N40P2X4_93X167X69N
- IC_Battery_Fuel_Gauge_ADI:SON50P200X200X80-9N -> Atomic_Footprints:SON50P200X200X80-9N
- IC_Button_Controller_ADI:DFN-8_DDB -> Atomic_Footprints:DFN-8_DDB
- IC_Button_Controller_ADI:TSOT-23_TS8 -> Atomic_Footprints:TSOT-23_TS8
- IC_Magnetometer_Memsic:PQFN50P300X300X100-16N -> Atomic_Footprints:PQFN50P300X300X100-16N
- IC_PowerManagementMosfet_TI:WSON_DLV_6 -> Atomic_Footprints:WSON_DLV_6
- IC_Wireless_BLE_uBlox:XCVR_NORA-W106-00B -> Atomic_Footprints:XCVR_NORA-W106-00B
- LED_Cree:LED_UHD1110-FKA-CL1A13R3Q1BBQFMF3 -> Atomic_Footprints:LED_UHD1110-FKA-CL1A13R3Q1BBQFMF3
- RECOM_DCDC_converters:RS3 -> Atomic_Footprints:RS3

## 3D models
- BGA8N40P2X4_93X167X69N.step -> MAX17048X.step
- LTC2954CTS8.step -> LTC2954ITS8-1.step
- LTC2954IDDB.step -> LTC2954IDDB-1.step
- MAX17048G_T10.step -> MAX17048G.step
- MEM2085-00-115-00-A_revA.STEP -> MEM2085-00-115-00-A.STEP
- USB4056-03-A_REVA2.step -> USB4056-03-A.step
- USB4730-GF-A_REVA.step -> USB4730-GF-A.step

Everything before this migration is kept in the tag pre-atomic of the Custom repository (git -C Custom log pre-atomic).

## Relink existing KiCad projects
1. In the Schematic Editor: Tools > Edit Symbol Library Links..., then pick each old library and choose its new Atomic_ library
2. Tools > Update Symbols from Library..., to take the renamed symbols and their fields
3. Tools > Update PCB from Schematic... (F8), to relink the footprints on the board

This app does not edit any KiCad project file itself; apply the three steps above by hand in every project that still references an old library.

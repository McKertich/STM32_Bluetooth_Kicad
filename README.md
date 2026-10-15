# STM32WB55 Bluetooth LE Board

A compact Bluetooth Low Energy board built around the STM32WB55CEU6
wireless microcontroller, designed in KiCad 10.

## Overview
- **MCU:** STM32WB55CEU6 (dual-core Arm Cortex-M4/M0+, BLE 5)
- **Power:** USB-C input with ESD protection (USBLC6-2SC6) and a
  3.3 V LDO (MIC5365)
- **RF:** filtered and matched RF path to a U.FL antenna connector
- **Clocks:** 32 MHz and 32.768 kHz crystals
- **Debug and I/O:** Tag-Connect TC2030 SWD header, UART header,
  reset button, status LED

## Status
Schematic complete (rev 1.0). PCB layout in progress.

## Repository contents
- `hardware/`: KiCad project files
- `libs/`: custom symbol and footprint libraries
- `docs/`: schematic PDF and renders (coming soon)

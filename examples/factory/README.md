# factory

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Runs the factory interface for display, buttons, RTC, IMU, battery ADC, SD card and wireless scanning.

## Hardware Required

ESP32-S3-LCD-3.16 development board and a USB data cable. Use a FAT32 microSD card for SD functions. Connect a compatible battery to measure battery voltage.

## How to Run

Open an ESP-IDF terminal in this directory and run with ESP-IDF v5.3.2:

```bash
idf.py set-target esp32s3 build flash monitor
```

## Expected Result

The screen shows test information; use the BOOT button to operate the factory interface.

## Troubleshooting

Insert a card for SD tests; use BOOT to switch screens and control tests.

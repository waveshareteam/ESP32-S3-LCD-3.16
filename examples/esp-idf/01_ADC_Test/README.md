# 01_ADC_Test

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Reads the onboard battery-voltage divider through ADC and prints raw readings and calculated voltage.

## Hardware Required

ESP32-S3-LCD-3.16 development board and a USB data cable. Connect a compatible battery to measure battery voltage.

## How to Run

Open an ESP-IDF terminal in this directory and run with an ESP-IDF version listed in the repository README:

```bash
idf.py set-target esp32s3 build flash monitor
```

## Expected Result

The log repeatedly shows raw ADC readings and calculated voltage.

## Troubleshooting

None yet.

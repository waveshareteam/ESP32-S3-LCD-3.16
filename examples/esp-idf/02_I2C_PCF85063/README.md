# 02_I2C_PCF85063

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Sets and reads the onboard PCF85063 real-time clock.

## Hardware Required

ESP32-S3-LCD-3.16 development board and a USB data cable.

## How to Run

Open an ESP-IDF terminal in this directory and run with an ESP-IDF version listed in the repository README:

```bash
idf.py set-target esp32s3 build flash monitor
```

## Expected Result

The log prints the RTC date and time periodically.

## Troubleshooting

The example sets a fixed initial date and time on every boot; adjust it before use.

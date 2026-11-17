# 02_PCF85063_Test

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Sets and reads the onboard PCF85063 real-time clock.

## Hardware Required

ESP32-S3-LCD-3.16 development board and a USB data cable.

## How to Run

Install the Arduino-ESP32 version listed in the repository README, set the sketchbook location to `examples/arduino/`, select **ESP32S3 Dev Module**, then open and upload the matching `.ino`. Use **115200** in the serial monitor.

| Tools menu | Value |
| --- | --- |
| Flash Size | 16MB (128Mb) |
| Partition Scheme | 16M Flash (3MB APP/9.9MB FATFS) |
| PSRAM | OPI PSRAM |
| USB CDC On Boot | Enabled |

## Expected Result

The log prints the RTC date and time periodically.

## Troubleshooting

The example sets a fixed initial date and time on every boot; adjust it before use.

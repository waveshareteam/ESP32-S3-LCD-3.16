# 08_LVGL_V9_Test

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Runs the LVGL 9 music interface on the RGB LCD.

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

The LCD displays the LVGL music demonstration.

## Troubleshooting

This is a graphical music-player demonstration without audio output.Landscape rotation and backlight cycling are enabled in `user_config.h` by default.

# 04_SD_Card

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Mounts a microSD card and reports card information and capacity.

## Hardware Required

ESP32-S3-LCD-3.16 development board and a USB data cable. Use a FAT32 microSD card for SD functions.

## How to Run

Open an ESP-IDF terminal in this directory and run with an ESP-IDF version listed in the repository README:

```bash
idf.py set-target esp32s3 build flash monitor
```

## Expected Result

The log shows the mounted card information and capacity.

## Troubleshooting

Check the card and FAT32 format if mounting fails; the read/write test is disabled by default.

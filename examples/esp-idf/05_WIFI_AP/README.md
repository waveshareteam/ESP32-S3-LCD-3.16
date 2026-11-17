# 05_WIFI_AP

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Creates a 2.4 GHz Wi-Fi access point and reports connected stations.

## Hardware Required

ESP32-S3-LCD-3.16 development board and a USB data cable.

## How to Run

Open an ESP-IDF terminal in this directory and run with an ESP-IDF version listed in the repository README:

```bash
idf.py set-target esp32s3 build flash monitor
```

## Expected Result

The access point is visible to a Wi-Fi client and accepts connections.

## Troubleshooting

The default SSID is `waveshare_esp32` with password `wav123456`; rebuild and upload after changing them.

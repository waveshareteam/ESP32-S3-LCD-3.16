# 06_WIFI_STA

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Connects to a 2.4 GHz Wi-Fi network and prints the assigned IP address.

## Hardware Required

ESP32-S3-LCD-3.16 development board and a USB data cable. A 2.4 GHz Wi-Fi access point is required.

## How to Run

Set the SSID and password in this example's Wi-Fi source before building.

Open an ESP-IDF terminal in this directory and run with an ESP-IDF version listed in the repository README:

```bash
idf.py set-target esp32s3 build flash monitor
```

## Expected Result

An IP address is printed after the board connects.

## Troubleshooting

The default SSID / password is `PDCN` / `1234567890`.

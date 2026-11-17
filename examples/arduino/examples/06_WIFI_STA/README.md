# 06_WIFI_STA

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Connects to a 2.4 GHz Wi-Fi network and prints the assigned IP address.

## Hardware Required

ESP32-S3-LCD-3.16 development board and a USB data cable. A 2.4 GHz Wi-Fi access point is required.

## How to Run

Set the SSID and password in this example's Wi-Fi source before building.

Install the Arduino-ESP32 version listed in the repository README, set the sketchbook location to `examples/arduino/`, select **ESP32S3 Dev Module**, then open and upload the matching `.ino`. Use **115200** in the serial monitor.

| Tools menu | Value |
| --- | --- |
| Flash Size | 16MB (128Mb) |
| Partition Scheme | 16M Flash (3MB APP/9.9MB FATFS) |
| PSRAM | OPI PSRAM |
| USB CDC On Boot | Enabled |

## Expected Result

An IP address is printed after the board connects.

## Troubleshooting

The default SSID / password is `PDCN` / `1234567890`.The program blocks while waiting for the network.

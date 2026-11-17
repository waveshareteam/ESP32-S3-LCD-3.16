# 02_PCF85063_Test

[English](README.md) | [简体中文](README_ZH.md)

## 功能

设置并读取板载 PCF85063 实时时钟。

## 硬件需求

ESP32-S3-LCD-3.16 开发板和可传输数据的 USB 线。

## 怎么运行

安装仓库首页所列版本的 Arduino-ESP32，将项目文件夹位置设为 `examples/arduino/`，选择 **ESP32S3 Dev Module**，打开本目录同名 `.ino` 后上传。串口监视器设为 **115200**。

| 工具菜单 | 设置 |
| --- | --- |
| Flash Size | 16MB (128Mb) |
| Partition Scheme | 16M Flash (3MB APP/9.9MB FATFS) |
| PSRAM | OPI PSRAM |
| USB CDC On Boot | Enabled |

## 预期现象

日志周期输出 RTC 日期和时间。

## 常见问题

示例每次启动都会设置固定的初始时间，使用前请按需修改。

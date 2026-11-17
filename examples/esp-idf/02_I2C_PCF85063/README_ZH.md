# 02_I2C_PCF85063

[English](README.md) | [简体中文](README_ZH.md)

## 功能

设置并读取板载 PCF85063 实时时钟。

## 硬件需求

ESP32-S3-LCD-3.16 开发板和可传输数据的 USB 线。

## 怎么运行

在本目录打开 ESP-IDF 终端，使用 仓库首页所列 ESP-IDF 版本 运行：

```bash
idf.py set-target esp32s3 build flash monitor
```

## 预期现象

日志周期输出 RTC 日期和时间。

## 常见问题

示例每次启动都会设置固定的初始时间，使用前请按需修改。

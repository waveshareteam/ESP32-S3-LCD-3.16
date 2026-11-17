# factory

[English](README.md) | [简体中文](README_ZH.md)

## 功能

运行出厂测试界面，包含显示、按键、RTC、IMU、电池 ADC、SD 卡及无线扫描。

## 硬件需求

ESP32-S3-LCD-3.16 开发板和可传输数据的 USB 线。 使用 SD 功能时需插入 FAT32 格式的 microSD 卡。 测量电池电压需连接匹配的电池。

## 怎么运行

在本目录打开 ESP-IDF 终端，使用 ESP-IDF v5.3.2 运行：

```bash
idf.py set-target esp32s3 build flash monitor
```

## 预期现象

屏幕显示外设测试信息，可通过 BOOT 按键操作出厂界面。

## 常见问题

SD 测试需要插卡；BOOT 用于切换界面和控制测试。

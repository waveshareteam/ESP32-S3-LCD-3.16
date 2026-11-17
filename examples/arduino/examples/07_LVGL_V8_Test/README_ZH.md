# 07_LVGL_V8_Test

[English](README.md) | [简体中文](README_ZH.md)

## 功能

在 RGB LCD 上运行 LVGL 8 音乐界面演示。

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

LCD 显示 LVGL 音乐演示界面。

## 常见问题

本例为音乐播放器界面的图形演示，不包含音频输出。 默认开启横屏旋转与背光明暗循环测试，可在 `user_config.h` 调整。

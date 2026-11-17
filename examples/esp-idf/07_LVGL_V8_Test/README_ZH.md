# 07_LVGL_V8_Test

[English](README.md) | [简体中文](README_ZH.md)

## 功能

在 RGB LCD 上运行 LVGL 8 音乐界面演示。

## 硬件需求

ESP32-S3-LCD-3.16 开发板和可传输数据的 USB 线。

## 怎么运行

在本目录打开 ESP-IDF 终端，使用 仓库首页所列 ESP-IDF 版本 运行：

```bash
idf.py set-target esp32s3 build flash monitor
```

## 预期现象

LCD 显示 LVGL 音乐演示界面。

## 常见问题

本例为音乐播放器界面的图形演示，不包含音频输出。

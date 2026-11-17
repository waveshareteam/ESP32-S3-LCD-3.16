# 04_SD_Card

[English](README.md) | [简体中文](README_ZH.md)

## 功能

挂载 microSD 卡并输出卡片信息与容量。

## 硬件需求

ESP32-S3-LCD-3.16 开发板和可传输数据的 USB 线。 使用 SD 功能时需插入 FAT32 格式的 microSD 卡。

## 怎么运行

在本目录打开 ESP-IDF 终端，使用 仓库首页所列 ESP-IDF 版本 运行：

```bash
idf.py set-target esp32s3 build flash monitor
```

## 预期现象

挂载成功后，日志显示卡片信息与容量。

## 常见问题

SD 挂载失败时检查卡片与 FAT32 格式；读写测试默认未启用。

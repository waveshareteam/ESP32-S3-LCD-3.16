# 04_SD_Card

[English](README.md) | [简体中文](README_ZH.md)

## 功能

挂载 microSD 卡并输出卡片信息与容量。

## 硬件需求

ESP32-S3-LCD-3.16 开发板和可传输数据的 USB 线。 使用 SD 功能时需插入 FAT32 格式的 microSD 卡。

## 怎么运行

安装仓库首页所列版本的 Arduino-ESP32，将项目文件夹位置设为 `examples/arduino/`，选择 **ESP32S3 Dev Module**，打开本目录同名 `.ino` 后上传。串口监视器设为 **115200**。

| 工具菜单 | 设置 |
| --- | --- |
| Flash Size | 16MB (128Mb) |
| Partition Scheme | 16M Flash (3MB APP/9.9MB FATFS) |
| PSRAM | OPI PSRAM |
| USB CDC On Boot | Enabled |

## 预期现象

挂载成功后，日志显示卡片信息与容量。

## 常见问题

SD 挂载失败时检查卡片与 FAT32 格式；读写测试默认未启用。

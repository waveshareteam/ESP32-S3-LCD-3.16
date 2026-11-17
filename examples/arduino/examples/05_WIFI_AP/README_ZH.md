# 05_WIFI_AP

[English](README.md) | [简体中文](README_ZH.md)

## 功能

创建 2.4 GHz Wi-Fi 热点并输出客户端连接信息。

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

客户端能够搜索并连接该 Wi-Fi 热点。

## 常见问题

默认 SSID 为 `ESP32_AP`，密码为 `12345678`，修改后需重新编译上传。

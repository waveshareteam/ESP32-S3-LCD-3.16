# 05_WIFI_AP

[English](README.md) | [简体中文](README_ZH.md)

## 功能

创建 2.4 GHz Wi-Fi 热点并输出客户端连接信息。

## 硬件需求

ESP32-S3-LCD-3.16 开发板和可传输数据的 USB 线。

## 怎么运行

在本目录打开 ESP-IDF 终端，使用 仓库首页所列 ESP-IDF 版本 运行：

```bash
idf.py set-target esp32s3 build flash monitor
```

## 预期现象

客户端能够搜索并连接该 Wi-Fi 热点。

## 常见问题

默认 SSID 为 `waveshare_esp32`，密码为 `wav123456`，修改后需重新编译上传。

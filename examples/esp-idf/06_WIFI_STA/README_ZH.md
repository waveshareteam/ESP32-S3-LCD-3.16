# 06_WIFI_STA

[English](README.md) | [简体中文](README_ZH.md)

## 功能

连接 2.4 GHz Wi-Fi 网络并输出分配到的 IP 地址。

## 硬件需求

ESP32-S3-LCD-3.16 开发板和可传输数据的 USB 线。 需要可用的 2.4 GHz Wi-Fi 热点。

## 怎么运行

编译前修改本示例 Wi-Fi 源码中的 SSID 和密码。

在本目录打开 ESP-IDF 终端，使用 仓库首页所列 ESP-IDF 版本 运行：

```bash
idf.py set-target esp32s3 build flash monitor
```

## 预期现象

连接成功后输出 IP 地址。

## 常见问题

默认 SSID / 密码为 `PDCN` / `1234567890`。

# 01_ADC_Test

[English](README.md) | [简体中文](README_ZH.md)

## 功能

通过 ADC 采集板载电池电压分压信号，输出原始读数和换算电压。

## 硬件需求

ESP32-S3-LCD-3.16 开发板和可传输数据的 USB 线。 测量电池电压需连接匹配的电池。

## 怎么运行

在本目录打开 ESP-IDF 终端，使用 仓库首页所列 ESP-IDF 版本 运行：

```bash
idf.py set-target esp32s3 build flash monitor
```

## 预期现象

日志持续输出 ADC 原始读数与换算电压。

## 常见问题

暂无。

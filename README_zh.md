# IRbaby-Firmware

[![Build and Release](https://github.com/Caffreyfans/IRbaby-firmware/actions/workflows/release.yml/badge.svg)](https://github.com/Caffreyfans/IRbaby-firmware/actions/workflows/release.yml)

ESP8266 红外遥控固件，支持通过 UDP/MQTT 控制红外设备，并提供 OTA、红外学习和 Home Assistant MQTT 发现能力。

[English doc](README.md) | [中文文档](README_zh.md)

## 功能

- [x] OTA 在线更新
- [x] MQTT 控制
- [x] UDP 控制
- [x] IRext 空调码库
- [x] 红外发送
- [x] 红外接收/学习
- [x] Home Assistant MQTT 自动发现
- [x] 可选二进制传感器上报

## 构建

本项目使用 PlatformIO：

```bash
pio run
```

可用环境：

- `esp8266-4m-base`
- `esp8266-2m-base`
- `esp8266-1m-base`

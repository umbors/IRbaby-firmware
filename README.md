# IRbaby-Firmware

[![Build and Release](https://github.com/Caffreyfans/IRbaby-firmware/actions/workflows/release.yml/badge.svg)](https://github.com/Caffreyfans/IRbaby-firmware/actions/workflows/release.yml)

ESP8266 infrared remote-control firmware with UDP/MQTT control, OTA updates, IR learning, and Home Assistant MQTT discovery.

[English doc](README.md) | [中文文档](README_zh.md)

## Features

- [x] OTA updates
- [x] MQTT control
- [x] UDP control
- [x] IRext AC code library
- [x] IR send
- [x] IR receive/learning
- [x] Home Assistant MQTT discovery
- [x] Optional binary sensor reporting

## Build

This project uses PlatformIO:

```bash
pio run
```

Available environments:

- `esp8266-4m-base`
- `esp8266-2m-base`
- `esp8266-1m-base`

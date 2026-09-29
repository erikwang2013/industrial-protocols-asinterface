# AS-Interface 协议包 — 需 Bihl+Wiedemann/Pepperl+Fuchs 网关桥接

> [English](README.en.md)

AS-Interface (AS-i, Actuator-Sensor Interface) 底层现场总线。通过 AS-i Master 网关（Bihl+Wiedemann BWU3540/BWU3675 或 Pepperl+Fuchs）桥接，内核 Bridge 层通信。

## 安装

```bash
composer require erikwang2013/industrial-protocols-asinterface
```

## 功能

AS-Interface 桥接、BridgeConnector 连接管理

## 所需硬件

Bihl+Wiedemann BWU3540/BWU3675、Pepperl+Fuchs VBA-4E-G20 AS-i Gateway

## 兼容框架

Laravel / Webman / Hyperf / ThinkPHP / Yii2 / Yii3 / Plain PHP

## 系统要求

- PHP >= 8.1
- AS-Interface Master 网关
- erikwang2013/industrial-protocols-kernel

## License

MIT — Copyright (c) 2026 erik <erik@erik.xyz> — https://erik.xyz

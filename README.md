English | [简体中文](README_CN.md)

# KVM Switch with USB HUB, TTL Serial Port and Bluetooth

A desktop KVM switch that also bundles a USB HUB, a TTL serial port and a Bluetooth module on one board — silkscreened **KVM&HUB&TTL**.

It switches between **two host PCs (PC1 / PC2)** from the front-panel button or the included infrared remote.

![KVM switch function layout](KVM-Switch-Tutorial/en/images/KVM切换器功能分布.png)

## Features

| Item | Detail |
|------|--------|
| Hosts | 2 (PC1 / PC2) |
| Switching | Front-panel button, infrared remote control |
| USB HUB | One USB Type-C input expands to three USB ports |
| TTL serial port | Pins left to right: `GND  RXD  TXD  TNOW  3V3  5V` |
| Bluetooth module | Connect over AT commands, or switch it to slave mode (Bluetooth 4.2) |
| Indicators | Power, PC1, PC2, UART |

## Modules

### 1. USB HUB

A single USB Type-C cable expands one USB port into three.

![USB HUB one-to-three](KVM-Switch-Tutorial/en/images/KVM切换器%20一分三.png)

### 2. TTL Serial Port

![TTL serial port pins](KVM-Switch-Tutorial/en/images/截图_20260316104812.png)

### 3. Bluetooth Module

![Bluetooth module](KVM-Switch-Tutorial/en/images/截图_20260316105733.png)

## Dual-End Switching

### 1. Two devices, both with monitors

Switch with the button or the infrared remote.

![Button and IR remote switching](KVM-Switch-Tutorial/en/images/KVM切换器.png)

### 2. Mainboard (no monitor) + host (with monitor)

Add a 4K HD HDMI capture card on the host side and use OBS or PotPlayer **on the host** to capture the screen of the **monitor-less mainboard**.

![Capture card wiring](KVM-Switch-Tutorial/en/images/KVM切换器%20%281%29.png)

The full wiring options (HDMI / Micro HDMI / DP) and the OBS and PotPlayer walkthroughs are in the tutorial.

## Language

| Language | Folder |
|----------|--------|
| English | [`en/`](KVM-Switch-Tutorial/en/) |
| Deutsch | [`de/`](KVM-Switch-Tutorial/de/) |
| Español | [`es/`](KVM-Switch-Tutorial/es/) |
| Français | [`fr/`](KVM-Switch-Tutorial/fr/) |
| Italiano | [`it/`](KVM-Switch-Tutorial/it/) |
| 日本語 | [`ja/`](KVM-Switch-Tutorial/ja/) |
| 한국어 | [`ko/`](KVM-Switch-Tutorial/ko/) |
| Português (BR) | [`pt-br/`](KVM-Switch-Tutorial/pt-br/) |
| Português (PT) | [`pt-pt/`](KVM-Switch-Tutorial/pt-pt/) |
| 简体中文 | [`zh-hans/`](KVM-Switch-Tutorial/zh-hans/) |
| 繁體中文 | [`zh-hant/`](KVM-Switch-Tutorial/zh-hant/) |

## Tutorial

| English | 中文 |
|---------|------|
| [KVM Switch Tutorial](KVM-Switch-Tutorial/en/kvm-switch-tutorial.md) | [KVM 切换器使用教程](KVM-Switch-Tutorial/zh-hans/kvm-switch-tutorial.md) |

Images are stored **only** under `KVM-Switch-Tutorial/en/images/`; every other language links to that one copy. Each tutorial page carries a language switcher on its first line.

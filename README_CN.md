[English](README.md) | 简体中文

# KVM 切换器（带 USB HUB、TTL 串口、蓝牙模块）

桌面式 KVM 切换器，同一块板子上集成了 USB HUB、TTL 串口和蓝牙模块 —— 板子丝印为 **KVM&HUB&TTL**。

通过面板按键或随附的红外遥控器，在**两台主机（PC1 / PC2）**之间切换。

![KVM 切换器功能分布](KVM-Switch-Tutorial/en/images/KVM切换器功能分布.png)

## 功能一览

| 项目 | 说明 |
|------|------|
| 主机数 | 2 台（PC1 / PC2） |
| 切换方式 | 面板按键、红外遥控 |
| USB HUB | 一路 USB Type-C 输入扩展出三路 USB |
| TTL 串口 | 引脚从左到右：`GND  RXD  TXD  TNOW  3V3  5V` |
| 蓝牙模块 | AT 指令连接，也可切到从机模式（蓝牙 4.2） |
| 指示灯 | 电源、PC1、PC2、UART |

## 单独模块功能

### 1、HUB 功能

一根 USB Type-C 线把一路 USB 扩展成三路。

![USB HUB 一分三](KVM-Switch-Tutorial/en/images/KVM切换器%20一分三.png)

### 2、TTL 串口

![TTL 串口引脚](KVM-Switch-Tutorial/en/images/截图_20260316104812.png)

### 3、蓝牙模块

![蓝牙模块](KVM-Switch-Tutorial/en/images/截图_20260316105733.png)

## 双端切换

### 1、设备 A + 设备 B（双端都有显示器）

用按键或红外遥控切换。

![按键切换与红外遥控切换](KVM-Switch-Tutorial/en/images/KVM切换器.png)

### 2、主板（无显示器）+ 主机（有显示器）

在主机侧再接一个 4K 高清 HDMI 采集卡，用 **主机上** 的 OBS 或 PotPlayer 采集 **无显示器主板** 的画面。

![采集卡接线](KVM-Switch-Tutorial/en/images/KVM切换器%20%281%29.png)

HDMI / Micro HDMI / DP 三种接线的完整走法，以及 OBS 和 PotPlayer 的操作步骤，见教程正文。

## 语言

| 语言 | 目录 |
|------|------|
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

## 教程

| 中文 | English |
|------|---------|
| [KVM 切换器使用教程](KVM-Switch-Tutorial/zh-hans/kvm-switch-tutorial.md) | [KVM Switch Tutorial](KVM-Switch-Tutorial/en/kvm-switch-tutorial.md) |

图片**只存放在 `KVM-Switch-Tutorial/en/images/` 一份**，其他语言统一引用这一份。每篇教程首行都有语言切换条。

[English](../en/kvm-switch-tutorial.md) | [Deutsch](../de/kvm-switch-tutorial.md) | [Español](../es/kvm-switch-tutorial.md) | [Français](../fr/kvm-switch-tutorial.md) | [Italiano](../it/kvm-switch-tutorial.md) | [日本語](../ja/kvm-switch-tutorial.md) | [한국어](../ko/kvm-switch-tutorial.md) | [Português (BR)](../pt-br/kvm-switch-tutorial.md) | [Português (PT)](../pt-pt/kvm-switch-tutorial.md) | 简体中文 | [繁體中文](../zh-hant/kvm-switch-tutorial.md)

# KVM切换器使用教程

KVM切换器包含HUB功能、TTL串口、蓝牙模块

![KVM切换器功能分布\.png](../en/images/KVM切换器功能分布.png)

## 单独模块功能

### 1、HUB功能

只需通过一根USB\-TypeC线即可实现一个USB接口拓展为三个USB接口

![KVM切换器 一分三\.png](../en/images/KVM切换器%20一分三.png)

### 2、TTL串口

针脚从左到右分别为 GND RXD TXD TNOW 3V3 5V

![截图\_20260316104812\.png](../en/images/截图_20260316104812.png)

### 3、蓝牙模块

![截图\_20260316105733\.png](../en/images/截图_20260316105733.png)

用at指令去连接，或者改成从模式，手机得走4\.2协议连接



## 双端切换

### 1、设备A\+设备B（双端都有显示器）

按键切换\&红外遥控器切换

![KVM切换器\.png](../en/images/KVM切换器.png)

### 2、主板（无显示器）\+主机（有显示器）

只需要额外使用一个 4K高清HDMI采集器 连接到主机端，在**主机端**使用OBS、PotPlayer等软件即可采集**主板（无显示器）**的画面

![KVM切换器 \(1\)\.png](../en/images/KVM切换器%20%281%29.png)

**4K高清HDMI采集器 接线操作**

根据主板的接口分以下三种接线操作

**HDMI接口**——\>HDMI线——\>采集器的HDMI接口——\> USB/Type\-C ——\>笔记本、电脑、一体机、手机/平板等显示器

**Micro HDMI接口**——\>Micro转HDMI转接头——\>HDMI线——\>采集器的HDMI接口——\> USB/Type\-C ——\>笔记本、电脑、一体机、手机/平板等显示器

**DP接口**——\>DP转HDMI转接头——\>HDMI线——\>采集器的HDMI接口——\> USB/Type\-C ——\>笔记本、电脑、一体机、手机/平板等显示器

![14\.jpg](../en/images/14.jpg)

**OBS操作指南**

![16\.jpg](../en/images/16.jpg)

**PotPlayer操作指南**

![17\.jpg](../en/images/17.jpg)





针脚图示例

![Ga0YbIHdTotpxhxyaWGc5t5Unzh\.png](../en/images/Ga0YbIHdTotpxhxyaWGc5t5Unzh.png)

![image\.png](../en/images/image.png)

![UART\&TTL\.png](../en/images/UART&TTL.png)


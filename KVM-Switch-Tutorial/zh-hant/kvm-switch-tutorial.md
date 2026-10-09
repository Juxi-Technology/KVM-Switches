[English](../en/kvm-switch-tutorial.md) | [Deutsch](../de/kvm-switch-tutorial.md) | [Español](../es/kvm-switch-tutorial.md) | [Français](../fr/kvm-switch-tutorial.md) | [Italiano](../it/kvm-switch-tutorial.md) | [日本語](../ja/kvm-switch-tutorial.md) | [한국어](../ko/kvm-switch-tutorial.md) | [Português (BR)](../pt-br/kvm-switch-tutorial.md) | [Português (PT)](../pt-pt/kvm-switch-tutorial.md) | [简体中文](../zh-hans/kvm-switch-tutorial.md) | 繁體中文

# KVM切換器使用教程

KVM切換器包含HUB功能、TTL串口、藍牙模組

![KVM切换器功能分布\.png](../en/images/KVM切换器功能分布.png)

## 單獨模組功能

### 1、HUB功能

只需通過一根USB\-TypeC線即可實現一個USB接口拓展為三個USB接口

![KVM切换器 一分三\.png](../en/images/KVM切换器%20一分三.png)

### 2、TTL串口

針腳從左到右分別為 GND RXD TXD TNOW 3V3 5V

![截图\_20260316104812\.png](../en/images/截图_20260316104812.png)

### 3、藍牙模組

![截图\_20260316105733\.png](../en/images/截图_20260316105733.png)

用at指令去連接，或者改成從模式，手機得走4\.2協定連接



## 雙端切換

### 1、裝置A\+裝置B（雙端都有顯示器）

按鍵切換\&紅外遙控器切換

![KVM切换器\.png](../en/images/KVM切换器.png)

### 2、主板（無顯示器）\+主機（有顯示器）

只需要額外使用一個 4K高清HDMI採集器 連接到主機端，在**主機端**使用OBS、PotPlayer等軟件即可採集**主板（無顯示器）**的畫面

![KVM切换器 \(1\)\.png](../en/images/KVM切换器%20%281%29.png)

**4K高清HDMI採集器 接線操作**

根據主板的接口分以下三種接線操作

**HDMI接口**——\>HDMI線——\>採集器的HDMI接口——\> USB/Type\-C ——\>筆記本、電腦、一體機、手機/平板等顯示器

**Micro HDMI接口**——\>Micro轉HDMI轉接頭——\>HDMI線——\>採集器的HDMI接口——\> USB/Type\-C ——\>筆記本、電腦、一體機、手機/平板等顯示器

**DP接口**——\>DP轉HDMI轉接頭——\>HDMI線——\>採集器的HDMI接口——\> USB/Type\-C ——\>筆記本、電腦、一體機、手機/平板等顯示器

![14\.jpg](../en/images/14.jpg)

**OBS操作指南**

![16\.jpg](../en/images/16.jpg)

**PotPlayer操作指南**

![17\.jpg](../en/images/17.jpg)





針腳圖示例

![Ga0YbIHdTotpxhxyaWGc5t5Unzh\.png](../en/images/Ga0YbIHdTotpxhxyaWGc5t5Unzh.png)

![image\.png](../en/images/image.png)

![UART\&TTL\.png](../en/images/UART&TTL.png)


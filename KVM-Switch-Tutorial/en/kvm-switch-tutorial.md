English | [Deutsch](../de/kvm-switch-tutorial.md) | [Español](../es/kvm-switch-tutorial.md) | [Français](../fr/kvm-switch-tutorial.md) | [Italiano](../it/kvm-switch-tutorial.md) | [日本語](../ja/kvm-switch-tutorial.md) | [한국어](../ko/kvm-switch-tutorial.md) | [Português (BR)](../pt-br/kvm-switch-tutorial.md) | [Português (PT)](../pt-pt/kvm-switch-tutorial.md) | [简体中文](../zh-hans/kvm-switch-tutorial.md) | [繁體中文](../zh-hant/kvm-switch-tutorial.md)

# KVM Switch Tutorial

The KVM switch includes a HUB function, a TTL serial port, and a Bluetooth module

![KVM切换器功能分布\.png](images/KVM切换器功能分布.png)

## Individual Module Functions

### 1. HUB Function

A single USB\-TypeC cable expands one USB port into three USB ports

![KVM切换器 一分三\.png](images/KVM切换器%20一分三.png)

### 2. TTL Serial Port

From left to right, the pins are GND RXD TXD TNOW 3V3 5V

![截图\_20260316104812\.png](images/截图_20260316104812.png)

### 3. Bluetooth Module

![截图\_20260316105733\.png](images/截图_20260316105733.png)

Use AT commands to connect, or switch it to slave mode; the phone must connect using the 4\.2 protocol



## Dual-End Switching

### 1. Device A \+ Device B (both ends have monitors)

Button switching \& infrared remote control switching

![KVM切换器\.png](images/KVM切换器.png)

### 2. Mainboard (no monitor) \+ Host (with monitor)

Simply connect an additional 4K HD HDMI capture card to the host side, and use software such as OBS or PotPlayer on the **host side** to capture the screen of the **mainboard (no monitor)**

![KVM切换器 \(1\)\.png](images/KVM切换器%20%281%29.png)

**4K HD HDMI Capture Card Wiring**

The following three wiring options are available depending on the mainboard's interface

**HDMI port**——\>HDMI cable——\>capture card's HDMI port——\> USB/Type\-C ——\>laptop, computer, all\-in\-one, phone/tablet and other displays

**Micro HDMI port**——\>Micro\-to\-HDMI adapter——\>HDMI cable——\>capture card's HDMI port——\> USB/Type\-C ——\>laptop, computer, all\-in\-one, phone/tablet and other displays

**DP port**——\>DP\-to\-HDMI adapter——\>HDMI cable——\>capture card's HDMI port——\> USB/Type\-C ——\>laptop, computer, all\-in\-one, phone/tablet and other displays

![14\.jpg](images/14.jpg)

**OBS Guide**

![16\.jpg](images/16.jpg)

**PotPlayer Guide**

![17\.jpg](images/17.jpg)





Pinout example

![Ga0YbIHdTotpxhxyaWGc5t5Unzh\.png](images/Ga0YbIHdTotpxhxyaWGc5t5Unzh.png)

![image\.png](images/image.png)

![UART\&TTL\.png](images/UART&TTL.png)


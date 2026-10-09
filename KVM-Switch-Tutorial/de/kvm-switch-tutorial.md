[English](../en/kvm-switch-tutorial.md) | Deutsch | [Español](../es/kvm-switch-tutorial.md) | [Français](../fr/kvm-switch-tutorial.md) | [Italiano](../it/kvm-switch-tutorial.md) | [日本語](../ja/kvm-switch-tutorial.md) | [한국어](../ko/kvm-switch-tutorial.md) | [Português (BR)](../pt-br/kvm-switch-tutorial.md) | [Português (PT)](../pt-pt/kvm-switch-tutorial.md) | [简体中文](../zh-hans/kvm-switch-tutorial.md) | [繁體中文](../zh-hant/kvm-switch-tutorial.md)

# Anleitung für den KVM-Switch

Der KVM-Switch enthält eine HUB-Funktion, eine TTL-Schnittstelle und ein Bluetooth-Modul

![KVM切换器功能分布\.png](../en/images/KVM切换器功能分布.png)

## Funktionen der einzelnen Module

### 1. HUB-Funktion

Mit nur einem USB\-TypeC-Kabel lässt sich ein USB-Anschluss zu drei USB-Anschlüssen erweitern

![KVM切换器 一分三\.png](../en/images/KVM切换器%20一分三.png)

### 2. TTL-Schnittstelle

Die Pins sind von links nach rechts: GND RXD TXD TNOW 3V3 5V

![截图\_20260316104812\.png](../en/images/截图_20260316104812.png)

### 3. Bluetooth-Modul

![截图\_20260316105733\.png](../en/images/截图_20260316105733.png)

Verwenden Sie AT-Befehle zum Verbinden, oder stellen Sie auf den Slave-Modus um; das Handy muss über das 4\.2-Protokoll verbinden



## Umschalten zwischen zwei Seiten

### 1. Gerät A\+Gerät B (beide Seiten haben einen Monitor)

Tastenumschaltung\&Umschaltung per Infrarot-Fernbedienung

![KVM切换器\.png](../en/images/KVM切换器.png)

### 2. Mainboard (ohne Monitor)\+Host-Rechner (mit Monitor)

Sie müssen nur zusätzlich eine 4K-UHD-HDMI-Capture-Card an die Host-Seite anschließen; auf der **Host-Seite** können Sie mit Software wie OBS, PotPlayer usw. das Bild des **Mainboards (ohne Monitor)** erfassen

![KVM切换器 \(1\)\.png](../en/images/KVM切换器%20%281%29.png)

**Verkabelung der 4K-UHD-HDMI-Capture-Card**

Je nach Anschluss des Mainboards gibt es die folgenden drei Verkabelungsvarianten

**HDMI-Anschluss**——\>HDMI-Kabel——\>HDMI-Anschluss der Capture-Card——\> USB/Type\-C ——\>Laptop, Computer, All-in-One-PC, Handy/Tablet und andere Displays

**Micro-HDMI-Anschluss**——\>Micro-auf-HDMI-Adapter——\>HDMI-Kabel——\>HDMI-Anschluss der Capture-Card——\> USB/Type\-C ——\>Laptop, Computer, All-in-One-PC, Handy/Tablet und andere Displays

**DP-Anschluss**——\>DP-auf-HDMI-Adapter——\>HDMI-Kabel——\>HDMI-Anschluss der Capture-Card——\> USB/Type\-C ——\>Laptop, Computer, All-in-One-PC, Handy/Tablet und andere Displays

![14\.jpg](../en/images/14.jpg)

**OBS-Anleitung**

![16\.jpg](../en/images/16.jpg)

**PotPlayer-Anleitung**

![17\.jpg](../en/images/17.jpg)





Beispiel für die Pinbelegung

![Ga0YbIHdTotpxhxyaWGc5t5Unzh\.png](../en/images/Ga0YbIHdTotpxhxyaWGc5t5Unzh.png)

![image\.png](../en/images/image.png)

![UART\&TTL\.png](../en/images/UART&TTL.png)


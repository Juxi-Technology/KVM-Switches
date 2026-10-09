[English](../en/kvm-switch-tutorial.md) | [Deutsch](../de/kvm-switch-tutorial.md) | [Español](../es/kvm-switch-tutorial.md) | Français | [Italiano](../it/kvm-switch-tutorial.md) | [日本語](../ja/kvm-switch-tutorial.md) | [한국어](../ko/kvm-switch-tutorial.md) | [Português (BR)](../pt-br/kvm-switch-tutorial.md) | [Português (PT)](../pt-pt/kvm-switch-tutorial.md) | [简体中文](../zh-hans/kvm-switch-tutorial.md) | [繁體中文](../zh-hant/kvm-switch-tutorial.md)

# Guide d'utilisation du commutateur KVM

Le commutateur KVM comprend une fonction HUB, un port série TTL et un module Bluetooth

![KVM切换器功能分布\.png](../en/images/KVM切换器功能分布.png)

## Fonctions des modules individuels

### 1. Fonction HUB

Un seul câble USB\-TypeC permet d'étendre un port USB en trois ports USB

![KVM切换器 一分三\.png](../en/images/KVM切换器%20一分三.png)

### 2. Port série TTL

Les broches de gauche à droite sont : GND RXD TXD TNOW 3V3 5V

![截图\_20260316104812\.png](../en/images/截图_20260316104812.png)

### 3. Module Bluetooth

![截图\_20260316105733\.png](../en/images/截图_20260316105733.png)

Utilisez des commandes AT pour vous connecter, ou passez en mode esclave ; le téléphone doit se connecter via le protocole 4\.2



## Basculement entre deux côtés

### 1. Appareil A\+Appareil B (les deux côtés ont un écran)

Basculement par bouton\&basculement par télécommande infrarouge

![KVM切换器\.png](../en/images/KVM切换器.png)

### 2. Carte mère (sans écran)\+ordinateur hôte (avec écran)

Il suffit d'utiliser en plus une carte de capture HDMI 4K UHD connectée au côté hôte ; sur le **côté hôte**, vous pouvez capturer l'image de la **carte mère (sans écran)** avec un logiciel comme OBS, PotPlayer, etc.

![KVM切换器 \(1\)\.png](../en/images/KVM切换器%20%281%29.png)

**Câblage de la carte de capture HDMI 4K UHD**

Selon le port de la carte mère, il existe les trois types de câblage suivants

**Port HDMI**——\>câble HDMI——\>port HDMI de la carte de capture——\> USB/Type\-C ——\>ordinateur portable, ordinateur, tout-en-un, téléphone/tablette et autres écrans

**Port Micro HDMI**——\>adaptateur Micro vers HDMI——\>câble HDMI——\>port HDMI de la carte de capture——\> USB/Type\-C ——\>ordinateur portable, ordinateur, tout-en-un, téléphone/tablette et autres écrans

**Port DP**——\>adaptateur DP vers HDMI——\>câble HDMI——\>port HDMI de la carte de capture——\> USB/Type\-C ——\>ordinateur portable, ordinateur, tout-en-un, téléphone/tablette et autres écrans

![14\.jpg](../en/images/14.jpg)

**Guide OBS**

![16\.jpg](../en/images/16.jpg)

**Guide PotPlayer**

![17\.jpg](../en/images/17.jpg)





Exemple de schéma des broches

![Ga0YbIHdTotpxhxyaWGc5t5Unzh\.png](../en/images/Ga0YbIHdTotpxhxyaWGc5t5Unzh.png)

![image\.png](../en/images/image.png)

![UART\&TTL\.png](../en/images/UART&TTL.png)


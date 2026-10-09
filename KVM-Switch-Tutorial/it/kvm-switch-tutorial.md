[English](../en/kvm-switch-tutorial.md) | [Deutsch](../de/kvm-switch-tutorial.md) | [Español](../es/kvm-switch-tutorial.md) | [Français](../fr/kvm-switch-tutorial.md) | Italiano | [日本語](../ja/kvm-switch-tutorial.md) | [한국어](../ko/kvm-switch-tutorial.md) | [Português (BR)](../pt-br/kvm-switch-tutorial.md) | [Português (PT)](../pt-pt/kvm-switch-tutorial.md) | [简体中文](../zh-hans/kvm-switch-tutorial.md) | [繁體中文](../zh-hant/kvm-switch-tutorial.md)

# Tutoriale d'uso del commutatore KVM

Il commutatore KVM include funzione HUB, porta seriale TTL e modulo Bluetooth

![KVM切换器功能分布\.png](../en/images/KVM切换器功能分布.png)

## Funzioni dei singoli moduli

### 1. Funzione HUB

È sufficiente un solo cavo USB\-TypeC per espandere una porta USB in tre porte USB

![KVM切换器 一分三\.png](../en/images/KVM切换器%20一分三.png)

### 2. Porta seriale TTL

I pin, da sinistra a destra, sono GND RXD TXD TNOW 3V3 5V

![截图\_20260316104812\.png](../en/images/截图_20260316104812.png)

### 3. Modulo Bluetooth

![截图\_20260316105733\.png](../en/images/截图_20260316105733.png)

Collegarlo con comandi at, oppure impostarlo in modalità slave; il telefono cellulare deve collegarsi tramite il protocollo 4\.2



## Commutazione tra due dispositivi

### 1. Dispositivo A\+Dispositivo B (entrambi gli estremi con monitor)

Commutazione tramite pulsante\&commutazione tramite telecomando a infrarossi

![KVM切换器\.png](../en/images/KVM切换器.png)

### 2. Scheda madre (senza monitor)\+Host (con monitor)

È sufficiente utilizzare in aggiunta un acquisitore HDMI 4K HD collegato al lato host; sul **lato host**, usando software come OBS, PotPlayer, è possibile acquisire l'immagine della **scheda madre (senza monitor)**

![KVM切换器 \(1\)\.png](../en/images/KVM切换器%20%281%29.png)

**Operazioni di collegamento dell'acquisitore HDMI 4K HD**

In base all'interfaccia della scheda madre, si distinguono le tre operazioni di collegamento seguenti

**Porta HDMI**——\>Cavo HDMI——\>Porta HDMI dell'acquisitore——\> USB/Type\-C ——\>Portatili, computer, all-in-one, cellulari/tablet e altri monitor

**Porta Micro HDMI**——\>Adattatore da Micro a HDMI——\>Cavo HDMI——\>Porta HDMI dell'acquisitore——\> USB/Type\-C ——\>Portatili, computer, all-in-one, cellulari/tablet e altri monitor

**Porta DP**——\>Adattatore da DP a HDMI——\>Cavo HDMI——\>Porta HDMI dell'acquisitore——\> USB/Type\-C ——\>Portatili, computer, all-in-one, cellulari/tablet e altri monitor

![14\.jpg](../en/images/14.jpg)

**Guida all'uso di OBS**

![16\.jpg](../en/images/16.jpg)

**Guida all'uso di PotPlayer**

![17\.jpg](../en/images/17.jpg)





Esempio dello schema dei pin

![Ga0YbIHdTotpxhxyaWGc5t5Unzh\.png](../en/images/Ga0YbIHdTotpxhxyaWGc5t5Unzh.png)

![image\.png](../en/images/image.png)

![UART\&TTL\.png](../en/images/UART&TTL.png)


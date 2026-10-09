[English](../en/kvm-switch-tutorial.md) | [Deutsch](../de/kvm-switch-tutorial.md) | Español | [Français](../fr/kvm-switch-tutorial.md) | [Italiano](../it/kvm-switch-tutorial.md) | [日本語](../ja/kvm-switch-tutorial.md) | [한국어](../ko/kvm-switch-tutorial.md) | [Português (BR)](../pt-br/kvm-switch-tutorial.md) | [Português (PT)](../pt-pt/kvm-switch-tutorial.md) | [简体中文](../zh-hans/kvm-switch-tutorial.md) | [繁體中文](../zh-hant/kvm-switch-tutorial.md)

# Tutorial de uso del conmutador KVM

El conmutador KVM incluye función HUB, puerto serie TTL y módulo Bluetooth

![KVM切换器功能分布\.png](../en/images/KVM切换器功能分布.png)

## Funciones de los módulos individuales

### 1. Función HUB

Basta con un solo cable USB\-TypeC para ampliar un puerto USB a tres puertos USB

![KVM切换器 一分三\.png](../en/images/KVM切换器%20一分三.png)

### 2. Puerto serie TTL

Los pines, de izquierda a derecha, son GND RXD TXD TNOW 3V3 5V

![截图\_20260316104812\.png](../en/images/截图_20260316104812.png)

### 3. Módulo Bluetooth

![截图\_20260316105733\.png](../en/images/截图_20260316105733.png)

Conéctelo con comandos at, o cámbielo al modo esclavo; el teléfono móvil debe conectarse mediante el protocolo 4\.2



## Conmutación entre dos dispositivos

### 1. Dispositivo A\+Dispositivo B (ambos extremos con monitor)

Conmutación por botón\&conmutación por mando a distancia por infrarrojos

![KVM切换器\.png](../en/images/KVM切换器.png)

### 2. Placa base (sin monitor)\+Host (con monitor)

Solo es necesario usar adicionalmente un capturador HDMI 4K HD conectado al extremo del host; en el **extremo del host**, utilizando software como OBS, PotPlayer, se puede capturar la imagen de la **placa base (sin monitor)**

![KVM切换器 \(1\)\.png](../en/images/KVM切换器%20%281%29.png)

**Operaciones de conexión del capturador HDMI 4K HD**

Según la interfaz de la placa base, se distinguen las tres operaciones de conexión siguientes

**Puerto HDMI**——\>Cable HDMI——\>Puerto HDMI del capturador——\> USB/Type\-C ——\>Portátiles, ordenadores, todo-en-uno, móviles/tabletas y otros monitores

**Puerto Micro HDMI**——\>Adaptador Micro a HDMI——\>Cable HDMI——\>Puerto HDMI del capturador——\> USB/Type\-C ——\>Portátiles, ordenadores, todo-en-uno, móviles/tabletas y otros monitores

**Puerto DP**——\>Adaptador DP a HDMI——\>Cable HDMI——\>Puerto HDMI del capturador——\> USB/Type\-C ——\>Portátiles, ordenadores, todo-en-uno, móviles/tabletas y otros monitores

![14\.jpg](../en/images/14.jpg)

**Guía de uso de OBS**

![16\.jpg](../en/images/16.jpg)

**Guía de uso de PotPlayer**

![17\.jpg](../en/images/17.jpg)





Ejemplo del diagrama de pines

![Ga0YbIHdTotpxhxyaWGc5t5Unzh\.png](../en/images/Ga0YbIHdTotpxhxyaWGc5t5Unzh.png)

![image\.png](../en/images/image.png)

![UART\&TTL\.png](../en/images/UART&TTL.png)


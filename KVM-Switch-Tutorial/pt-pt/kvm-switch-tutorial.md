[English](../en/kvm-switch-tutorial.md) | [Deutsch](../de/kvm-switch-tutorial.md) | [Español](../es/kvm-switch-tutorial.md) | [Français](../fr/kvm-switch-tutorial.md) | [Italiano](../it/kvm-switch-tutorial.md) | [日本語](../ja/kvm-switch-tutorial.md) | [한국어](../ko/kvm-switch-tutorial.md) | [Português (BR)](../pt-br/kvm-switch-tutorial.md) | Português (PT) | [简体中文](../zh-hans/kvm-switch-tutorial.md) | [繁體中文](../zh-hant/kvm-switch-tutorial.md)

# Tutorial de utilização do comutador KVM

O comutador KVM inclui função HUB, porta série TTL e módulo Bluetooth

![KVM切换器功能分布\.png](../en/images/KVM切换器功能分布.png)

## Funções dos módulos individuais

### 1. Função HUB

Basta utilizar um único cabo USB\-TypeC para expandir uma interface USB em três interfaces USB

![KVM切换器 一分三\.png](../en/images/KVM切换器%20一分三.png)

### 2. Porta série TTL

Os pinos, da esquerda para a direita, são GND RXD TXD TNOW 3V3 5V

![截图\_20260316104812\.png](../en/images/截图_20260316104812.png)

### 3. Módulo Bluetooth

![截图\_20260316105733\.png](../en/images/截图_20260316105733.png)

Utilize comandos AT para conectar, ou mude para o modo escravo; o telemóvel tem de se conectar pelo protocolo 4\.2



## Comutação entre dois dispositivos

### 1. Dispositivo A\+Dispositivo B (ambos os lados têm monitor)

Comutação por botão\&comutação por telecomando de infravermelhos

![KVM切换器\.png](../en/images/KVM切换器.png)

### 2. Placa-mãe (sem monitor)\+Computador host (com monitor)

Basta utilizar adicionalmente um capturador HDMI 4K de alta definição ligado ao lado do host; no **lado do host**, utilize softwares como OBS e PotPlayer para capturar a imagem da **placa-mãe (sem monitor)**

![KVM切换器 \(1\)\.png](../en/images/KVM切换器%20%281%29.png)

**Operação de ligação do capturador HDMI 4K de alta definição**

De acordo com a interface da placa-mãe, a operação de ligação é dividida nos três tipos a seguir

**Interface HDMI**——\>Cabo HDMI——\>Interface HDMI do capturador——\> USB/Type\-C ——\>portátil, computador, tudo-em-um, telemóvel/tablet e outros monitores

**Interface Micro HDMI**——\>Adaptador Micro para HDMI——\>Cabo HDMI——\>Interface HDMI do capturador——\> USB/Type\-C ——\>portátil, computador, tudo-em-um, telemóvel/tablet e outros monitores

**Interface DP**——\>Adaptador DP para HDMI——\>Cabo HDMI——\>Interface HDMI do capturador——\> USB/Type\-C ——\>portátil, computador, tudo-em-um, telemóvel/tablet e outros monitores

![14\.jpg](../en/images/14.jpg)

**Guia de operação do OBS**

![16\.jpg](../en/images/16.jpg)

**Guia de operação do PotPlayer**

![17\.jpg](../en/images/17.jpg)





Exemplo de diagrama de pinos

![Ga0YbIHdTotpxhxyaWGc5t5Unzh\.png](../en/images/Ga0YbIHdTotpxhxyaWGc5t5Unzh.png)

![image\.png](../en/images/image.png)

![UART\&TTL\.png](../en/images/UART&TTL.png)


[English](../en/kvm-switch-tutorial.md) | [Deutsch](../de/kvm-switch-tutorial.md) | [Español](../es/kvm-switch-tutorial.md) | [Français](../fr/kvm-switch-tutorial.md) | [Italiano](../it/kvm-switch-tutorial.md) | [日本語](../ja/kvm-switch-tutorial.md) | [한국어](../ko/kvm-switch-tutorial.md) | Português (BR) | [Português (PT)](../pt-pt/kvm-switch-tutorial.md) | [简体中文](../zh-hans/kvm-switch-tutorial.md) | [繁體中文](../zh-hant/kvm-switch-tutorial.md)

# Tutorial de uso do switch KVM

O switch KVM inclui função HUB, porta serial TTL e módulo Bluetooth

![KVM切换器功能分布\.png](../en/images/KVM切换器功能分布.png)

## Funções dos módulos individuais

### 1. Função HUB

Basta usar um único cabo USB\-TypeC para expandir uma interface USB em três interfaces USB

![KVM切换器 一分三\.png](../en/images/KVM切换器%20一分三.png)

### 2. Porta serial TTL

Os pinos, da esquerda para a direita, são GND RXD TXD TNOW 3V3 5V

![截图\_20260316104812\.png](../en/images/截图_20260316104812.png)

### 3. Módulo Bluetooth

![截图\_20260316105733\.png](../en/images/截图_20260316105733.png)

Use comandos AT para conectar, ou mude para o modo escravo; o celular precisa se conectar pelo protocolo 4\.2



## Alternância entre dois dispositivos

### 1. Dispositivo A\+Dispositivo B (ambos os lados têm monitor)

Alternância por botão\&alternância por controle remoto de infravermelho

![KVM切换器\.png](../en/images/KVM切换器.png)

### 2. Placa-mãe (sem monitor)\+Computador host (com monitor)

Basta usar adicionalmente um capturador HDMI 4K de alta definição conectado ao lado do host; no **lado do host**, use softwares como OBS e PotPlayer para capturar a imagem da **placa-mãe (sem monitor)**

![KVM切换器 \(1\)\.png](../en/images/KVM切换器%20%281%29.png)

**Operação de conexão do capturador HDMI 4K de alta definição**

De acordo com a interface da placa-mãe, a operação de conexão é dividida nos três tipos a seguir

**Interface HDMI**——\>Cabo HDMI——\>Interface HDMI do capturador——\> USB/Type\-C ——\>notebook, computador, tudo-em-um, celular/tablet e outros monitores

**Interface Micro HDMI**——\>Adaptador Micro para HDMI——\>Cabo HDMI——\>Interface HDMI do capturador——\> USB/Type\-C ——\>notebook, computador, tudo-em-um, celular/tablet e outros monitores

**Interface DP**——\>Adaptador DP para HDMI——\>Cabo HDMI——\>Interface HDMI do capturador——\> USB/Type\-C ——\>notebook, computador, tudo-em-um, celular/tablet e outros monitores

![14\.jpg](../en/images/14.jpg)

**Guia de operação do OBS**

![16\.jpg](../en/images/16.jpg)

**Guia de operação do PotPlayer**

![17\.jpg](../en/images/17.jpg)





Exemplo de diagrama de pinos

![Ga0YbIHdTotpxhxyaWGc5t5Unzh\.png](../en/images/Ga0YbIHdTotpxhxyaWGc5t5Unzh.png)

![image\.png](../en/images/image.png)

![UART\&TTL\.png](../en/images/UART&TTL.png)


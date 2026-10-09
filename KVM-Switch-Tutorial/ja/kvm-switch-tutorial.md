[English](../en/kvm-switch-tutorial.md) | [Deutsch](../de/kvm-switch-tutorial.md) | [Español](../es/kvm-switch-tutorial.md) | [Français](../fr/kvm-switch-tutorial.md) | [Italiano](../it/kvm-switch-tutorial.md) | 日本語 | [한국어](../ko/kvm-switch-tutorial.md) | [Português (BR)](../pt-br/kvm-switch-tutorial.md) | [Português (PT)](../pt-pt/kvm-switch-tutorial.md) | [简体中文](../zh-hans/kvm-switch-tutorial.md) | [繁體中文](../zh-hant/kvm-switch-tutorial.md)

# KVM切替器の使用チュートリアル

KVM切替器にはHUB機能、TTLシリアルポート、Bluetoothモジュールが含まれています

![KVM切换器功能分布\.png](../en/images/KVM切换器功能分布.png)

## 単体モジュールの機能

### 1、HUB機能

USB\-TypeCケーブル1本だけで、1つのUSBインターフェースを3つのUSBインターフェースに拡張できます

![KVM切换器 一分三\.png](../en/images/KVM切换器%20一分三.png)

### 2、TTLシリアルポート

ピンは左から右へそれぞれ GND RXD TXD TNOW 3V3 5V です

![截图\_20260316104812\.png](../en/images/截图_20260316104812.png)

### 3、Bluetoothモジュール

![截图\_20260316105733\.png](../en/images/截图_20260316105733.png)

ATコマンドで接続するか、スレーブモードに変更します。スマートフォンは4\.2プロトコルで接続する必要があります



## 両端切替

### 1、デバイスA\+デバイスB（両端ともにディスプレイあり）

ボタン切替\&赤外線リモコン切替

![KVM切换器\.png](../en/images/KVM切换器.png)

### 2、マザーボード（ディスプレイなし）\+ホスト機（ディスプレイあり）

追加で 4K HD HDMIキャプチャーボード を1台用意してホスト側に接続し、**ホスト側**でOBS、PotPlayerなどのソフトウェアを使えば、**マザーボード（ディスプレイなし）**の画面をキャプチャできます

![KVM切换器 \(1\)\.png](../en/images/KVM切换器%20%281%29.png)

**4K HD HDMIキャプチャーボード 配線作業**

マザーボードのインターフェースに応じて、以下の3種類の配線作業に分かれます

**HDMIインターフェース**——\>HDMIケーブル——\>キャプチャーボードのHDMIインターフェース——\> USB/Type\-C ——\>ノートパソコン、パソコン、一体型パソコン、スマートフォン/タブレットなどのディスプレイ

**Micro HDMIインターフェース**——\>Micro-HDMI変換アダプター——\>HDMIケーブル——\>キャプチャーボードのHDMIインターフェース——\> USB/Type\-C ——\>ノートパソコン、パソコン、一体型パソコン、スマートフォン/タブレットなどのディスプレイ

**DPインターフェース**——\>DP-HDMI変換アダプター——\>HDMIケーブル——\>キャプチャーボードのHDMIインターフェース——\> USB/Type\-C ——\>ノートパソコン、パソコン、一体型パソコン、スマートフォン/タブレットなどのディスプレイ

![14\.jpg](../en/images/14.jpg)

**OBS操作ガイド**

![16\.jpg](../en/images/16.jpg)

**PotPlayer操作ガイド**

![17\.jpg](../en/images/17.jpg)





ピン配置図の例

![Ga0YbIHdTotpxhxyaWGc5t5Unzh\.png](../en/images/Ga0YbIHdTotpxhxyaWGc5t5Unzh.png)

![image\.png](../en/images/image.png)

![UART\&TTL\.png](../en/images/UART&TTL.png)


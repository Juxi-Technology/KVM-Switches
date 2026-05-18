# KVM-Switches

The KVM switch includes HUB functionality, TTL serial port, and Bluetooth module 

![img](https://juxitech.feishu.cn/space/api/box/stream/download/asynccode/?code=MDU0NjcwNmZkYzU5Y2EwMjk5ZDZmOTYwYTM0ODI5NTdfSlRDNncxZEJKZktMYlFtS2dLd1A1Q2RoY0RiQ3FNUmhfVG9rZW46S2FkVmJpZFZzb2R0Ykd4ZTJiSWNkcDFqbkloXzE3NzkwOTE1ODY6MTc3OTA5NTE4Nl9WNA)

## Individual module functionality

### 1. HUB Function

A single USB-TypeC cable can expand one USB port into three USB ports 

![img](https://juxitech.feishu.cn/space/api/box/stream/download/asynccode/?code=ODg1Y2EyOWQzOGY0MmM0N2Y5MzE3MzY3NTRkMGI0MDhfTEx0VmR3MkhmNm5ydTJ3ZUo2V2o1bVV1cmRnblVtQkNfVG9rZW46SXdpamJhQVVsb2hWRDJ4Uzg4aGNhYmd2bjRiXzE3NzkwOTE1ODY6MTc3OTA5NTE4Nl9WNA)

### 2. TTL Serial Port

The pins from left to right are GND, RXD, TXD, TNOW, 3V3, and 5V, respectively. 

![img](https://juxitech.feishu.cn/space/api/box/stream/download/asynccode/?code=MjljMjEyNzBhZGI5NzUyZmQ2MGVhZGUxMDQ3NGFiMjNfZ2lVbFhBM1c3dTFic3Z4QzRCYUNWV0t6cXpTZU9KSzhfVG9rZW46TDFVZ2I3VlRybzE1TTZ4VWRJeGNFQ1BvbmtiXzE3NzkwOTE1ODY6MTc3OTA5NTE4Nl9WNA)

### 3. Bluetooth Module

![img](https://juxitech.feishu.cn/space/api/box/stream/download/asynccode/?code=Yzg3ZThjMmE2ZmVkNzQ1ZjcwNDU3YTUxOWI0MzE1ZDdfTFBTUUhla1FCWlA1RzFmdnFuc3A0ak9KM2ViZURGY0FfVG9rZW46SmlnVGJodGJPb0RTWG14aTl3cGNvRlJ6blNjXzE3NzkwOTE1ODY6MTc3OTA5NTE4Nl9WNA)

Connect using AT commands, or change to slave mode, and the phone must connect via the 4.2 protocol 

## Double-ended switching

### 1. Device A + Device B (both ends have monitors)

Button Switch & Infrared Remote Control Switch

![img](https://juxitech.feishu.cn/space/api/box/stream/download/asynccode/?code=MjA4NTg0MzAxYWM5YTQzYzQyYmVmN2MyNWY0OWM3MzZfWmZtZ1hKNGZFYVBqaXhUZE9OaHoyT3dqZFZpd2YxODhfVG9rZW46WTdCUWJ5Q2tsb2FodTB4QXVKSWNWaXVkbktnXzE3NzkwOTE1ODY6MTc3OTA5NTE4Nl9WNA)

### 2. Motherboard (without monitor) + Host (with monitor)

Only need toadditionallyuse a 4K HD HDMI capture device connected to the host, and then**on the host**use software such as OBS and Potplay to capture**the motherboard (without a monitor)**screen

![img](https://juxitech.feishu.cn/space/api/box/stream/download/asynccode/?code=OGExODIwZTBlOGM3Y2E3ZTY5N2Y2ZDIzM2ZhZjY2MTlfakxlb1RNRFgzUmVHWVBVamN3NzB6M0hjdXZFbVpNaHJfVG9rZW46TzRkSWI0NlBDb2QxOXh4T2QyRmNDZ3hpbmZmXzE3NzkwOTE1ODY6MTc3OTA5NTE4Nl9WNA)

**4K HD HDMI Capture Device Wiring Operation**

According to the motherboard interface, there are the following three wiring operations 

**HDMI Interface** ——> HDMI Cable ——> HDMI Interface of the Collector ——> USB/Type-C ——> Displays such as Laptops, Computers, All in One, Phones/Tablets, etc.

**Micro HAMI Interface** ——> Micro to HDMI Adapter ——> HDMI Cable ——> HDMI Interface of the Collector ——> USB/Type-C ——> Displays such as Laptops, Computers, All in One, Phones/Tablets, etc.

**DP Interface** ——> DP to HDMI Adapter ——> HDMI Cable ——> HDMI Interface of the Collector ——> USB/Type-C ——> Displays such as Laptops, Computers, All in One, Phones/Tablets, etc.

![img](https://juxitech.feishu.cn/space/api/box/stream/download/asynccode/?code=MDA1ODA3OTI4MDE5YjlhZjk1NDQ3M2Q1NzExYTBiYzNfY2ZDaXFEeHFTTkhPd2RkcEIwSjlwMFc0Slo4WEhINm1fVG9rZW46T0tOaWIxckk0b2pKVGd4amRJVmNvTGprbmJmXzE3NzkwOTE1ODY6MTc3OTA5NTE4Nl9WNA)

**OBS Operation Guide**

![img](https://juxitech.feishu.cn/space/api/box/stream/download/asynccode/?code=NmYxYmUzNzllYjkyMjk3YjU0NzA2MGM3YTUwMjQwZTJfTEVManNIQXMxM3NYcTJSM050ajM0RjU3SUNPYW5xYmxfVG9rZW46QjhxS2JzZTNvb0NNTXF4Y3NsQ2NFVmJ0bkdkXzE3NzkwOTE1ODY6MTc3OTA5NTE4Nl9WNA)

**Potplayer Operation Guide**

![img](https://juxitech.feishu.cn/space/api/box/stream/download/asynccode/?code=MzAwMGNkNDIxNGM4NTk1OTM4Yzc1ZTZkNWMyMjI1MzlfVEhHVG1uZ3ZrRkVNZEtpZnM4TXA2aE1meklqSUZpQVpfVG9rZW46TDlJRmI5dUMyb2M3cGV4a0JlNWM5ZEdzbmViXzE3NzkwOTE1ODY6MTc3OTA5NTE4Nl9WNA)

Example of Pin Diagram

![img](https://juxitech.feishu.cn/space/api/box/stream/download/asynccode/?code=OWU2ZmFiODlhYmM3NWIyZWI1NDg2MWU4NTM5MGRlYzJfYTVpc1BvWGZaa2x6QWxKUWFjYldUTjVtaHlJVnZXN0lfVG9rZW46R2h6UmJzYTd4b0xldjV4WlcxRGNxRFcybm9oXzE3NzkwOTE1ODY6MTc3OTA5NTE4Nl9WNA)![img](https://juxitech.feishu.cn/space/api/box/stream/download/asynccode/?code=MGIzZTc4ZDhlNjJhMTAwY2M1ZWQ0YWM5ZTZhOGY5ZDdfMWhhaEVKSDFaM1JndjNOcjQ0dkFlYUh1M0dMaFAxYzlfVG9rZW46S2tmS2JDcnZUb05mdWJ4akRRTGNRbVJpbjZiXzE3NzkwOTE1ODY6MTc3OTA5NTE4Nl9WNA)

![img](https://juxitech.feishu.cn/space/api/box/stream/download/asynccode/?code=YzE2NmZjOWY4OGJhMzYxYTBkYzIxMjU3NDgzMmM2NjFfaXBJS2E2Q0Q1Vlptd2VDcTNYbGtDZWJoSjJGSndDbVJfVG9rZW46UkhkTGJaNFR5b1JmdmZ4cHJ6dmNUUXZDbmZiXzE3NzkwOTE1ODY6MTc3OTA5NTE4Nl9WNA)

# KVM-Switches

The KVM switch includes HUB functionality, TTL serial port, and Bluetooth module 

<img width="574" height="414" alt="image" src="https://github.com/user-attachments/assets/6f6d43f9-cf21-4c6b-af47-846b88656313" />

## Individual module functionality

### 1. HUB Function

A single USB-TypeC cable can expand one USB port into three USB ports 

<img width="575" height="386" alt="image" src="https://github.com/user-attachments/assets/c1f15ee3-c515-43ec-b948-6632deb71de2" />

### 2. TTL Serial Port

The pins from left to right are GND, RXD, TXD, TNOW, 3V3, and 5V, respectively. 

<img width="769" height="551" alt="image" src="https://github.com/user-attachments/assets/04bf9910-07bd-49b5-804d-eb2235827746" />

### 3. Bluetooth Module

<img width="761" height="524" alt="image" src="https://github.com/user-attachments/assets/351310c3-b529-48dc-9419-babce731c9a9" />

Connect using AT commands, or change to slave mode, and the phone must connect via the 4.2 protocol 

## Double-ended switching

### 1. Device A + Device B (both ends have monitors)

Button Switch & Infrared Remote Control Switch

<img width="1149" height="504" alt="image" src="https://github.com/user-attachments/assets/47dcba7b-3a5f-4024-8773-0fbadc6d63bd" />

### 2. Motherboard (without monitor) + Host (with monitor)

Only need toadditionallyuse a 4K HD HDMI capture device connected to the host, and then**on the host**use software such as OBS and Potplay to capture**the motherboard (without a monitor)**screen

<img width="572" height="441" alt="image" src="https://github.com/user-attachments/assets/0ea4799c-4274-4591-890d-54566725af7a" />
<img width="497" height="383" alt="image" src="https://github.com/user-attachments/assets/ab8bd898-fd8c-4266-9ae7-01bfe621dbee" />

**4K HD HDMI Capture Device Wiring Operation**

According to the motherboard interface, there are the following three wiring operations 

**HDMI Interface** ——> HDMI Cable ——> HDMI Interface of the Collector ——> USB/Type-C ——> Displays such as Laptops, Computers, All in One, Phones/Tablets, etc.

**Micro HAMI Interface** ——> Micro to HDMI Adapter ——> HDMI Cable ——> HDMI Interface of the Collector ——> USB/Type-C ——> Displays such as Laptops, Computers, All in One, Phones/Tablets, etc.

**DP Interface** ——> DP to HDMI Adapter ——> HDMI Cable ——> HDMI Interface of the Collector ——> USB/Type-C ——> Displays such as Laptops, Computers, All in One, Phones/Tablets, etc.

<img width="556" height="493" alt="image" src="https://github.com/user-attachments/assets/376ca64a-f2d0-4906-8539-012f3f05f675" />

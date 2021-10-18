# Acer Aspire A515-51G i7-8550U/8GB/MX130 - my daily driver

![12313](https://ghproxy.com/https://github.com/Maserhe/PIc-Bed/blob/master/typora/202110182105789.png)

GeeKbench 跑分基本持平**MacBook Pro (13-inch Mid 2019) Intel Core i5-8257U @ 1.4 GHz (4 cores)** 



## OpenCore 0.74

https://github.com/acidanthera/OpenCorePkg



## What's Working...
 - [x] Audio & headphone jack
 - [x] CPU Speedstep
 - [x] iGPU with disabled dGPU
 - [x] Fully Functional QE/CI Enabled Graphics
 - [x] Battery Management
 - [x] ACPI Display brightness with hot keys / slider
 - [x] Ethernet
 - [x] HDMI + Audio
 - [x] Smart Touchpad + Gestures (using Basic Mode)
 - [x] WebCam
 - [x] Usb 3.0 + Type C
 - [x] WiFi (2.4 + 5GHz) by using BCM94352z （自己新买网卡更换的）
 - [x] Native hotkey support with Fn keys



## Installation

 ### BIOS Settings
* *Security* → Set supervisor password (to disable secure boot)
* *Security* → Password on boot → **Disable**
* *Boot* → Secure Boot → **Disable**
* *Boot* → Boot Mode → **UEFI**
* *Main* → Touchpad → Set touchpad mode → **Basic** *TODO: Advance Mode*
* *Main* → Lid Open resume → **Enabled**


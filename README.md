# ASUS-P8B75-M-LE-HACKINTOSH

## Specifications
| Component | Details |
|:---:|:---:|
| CPU | Intel Xeon E3-1230v2 |
| RAM | 8GB DDR3 1600Mhz x2 |
| MB | ASUS P8B75-M LE |
| Audio | VT1708S |
| SSD | Crucial M500 120GB |
| HDD | TOSHIBA DT01ACA200 1TB |
| iGPU | N / A |
| dGPU | MSI N730K-2GD5 |
<br>

## Supported Versions
- macOS Catalina 10.15.7
- macOS Big Sur 11.6.5
- macOS Monterey 12.0 (Not tested)
<br>

## Known Issues
Most parts are working well, except the following.

| Component | Status | Description |
|:---|:---|:---|
| Microphone | Working, but defective | The input sound gets crackled with input volume turned to high level in settings.<br> |

<br>

## Recommended BIOS Settings
Load optimized defaults firstly, then save changes and reboot into BIOS to continue the following parts.
- Advanced 
  - CPU Configuration \ Intel Virtualization Technology : **Enabled**
  - PCH Configuration \ Intel Rapid Start Technology \ Intel Rapid Start Technology : **Disabled**
  - PCH Configuration \ Intel Smart Connect Technology \ ISCT Configuration : **Disabled**
  - SATA Configuration \ SATA Mode Selection : **AHCI**
  - System Agent Configuration \ Memory Remap Feature : **Enabled**
  - USB Configuration \ Intel xHCI Mode : **Enabled**
  - USB Configuration \ EHCI Hand-off : **Enabled**
  - Onboard Devices Configuration \ Serial Port : **Disabled**
  - Onboard Devices Configuration \ Parallel Port : **Disabled**

<br>

- Boot
  - Fast Boot : **Disabled**
  - CSM (Compatibility Support Module) \ Launch CSM : **Disabled**
  - Secure Boot menu \ OS Type : **Other OS**

<br>

## Screenshots
<div align="center">
<img src="https://raw.githubusercontent.com/mfpss95134/ASUS-P8B75-M-LE-HACKINTOSH/main/IMAGEs/01.png">
<img src="https://raw.githubusercontent.com/mfpss95134/ASUS-P8B75-M-LE-HACKINTOSH/main/IMAGEs/02.png">
<img src="https://raw.githubusercontent.com/mfpss95134/ASUS-P8B75-M-LE-HACKINTOSH/main/IMAGEs/03.png">
<img src="https://raw.githubusercontent.com/mfpss95134/ASUS-P8B75-M-LE-HACKINTOSH/main/IMAGEs/04.png">
<img src="https://raw.githubusercontent.com/mfpss95134/ASUS-P8B75-M-LE-HACKINTOSH/main/IMAGEs/05.png">
<img src="https://raw.githubusercontent.com/mfpss95134/ASUS-P8B75-M-LE-HACKINTOSH/main/IMAGEs/06.png">
<div align="left">
<br>

## Reference
- <https://zhuanlan.zhihu.com/p/266400995>
- <https://blog.csdn.net/weixin_42525211/article/details/112126322>
<br>

## Credits
- [**Apple**](https://www.apple.com/tw/) for the macOS.
- [**Dortania**](https://github.com/dortania) for the great guides.
- [**Acidanthera**](https://github.com/acidanthera) for [AppleALC](https://github.com/acidanthera/AppleALC), [Lilu](https://github.com/acidanthera/Lilu), [OpenCore](https://github.com/acidanthera/OpenCorePkg), [VoodooPS2](https://github.com/acidanthera/VoodooPS2), [VirtualSMC](https://github.com/acidanthera/VirtualSMC), [WhateverGreen](https://github.com/acidanthera/WhateverGreen)
- [**RehabMan**](https://github.com/RehabMan) for [USBInjectAll](https://github.com/RehabMan/OS-X-USB-Inject-All)

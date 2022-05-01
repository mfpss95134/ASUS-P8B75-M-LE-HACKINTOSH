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

## Recommended BIOS Settings / Modifications
- Disable
  - Fast Boot
  - Secure Boot
  - Serial/COM Port
  - Parallel Port
  - VT-d
  - CSM
  - Intel SGX
  - Intel Platform Trust
  - CFG Lock
  
  
- Enable
  - VT-x
  - Hyper-Threading
  - Execute Disable Bit
  - EHCI/XHCI Hand-off
  - OS type: Windows 8.1/10 UEFI Mode
  - DVMT Pre-Allocated(iGPU Memory): 32MB
  - SATA Mode: AHCI
<br>

## Screenshots
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

# ASUS-P8B75-M-LE-HACKINTOSH

## Specifications
| Component | Details |
|:---:|:---:|
| CPU | Intel Xeon E3-1230v2 |
| RAM | Trascend 8GB DDR3 1600Mhz x2 |
| MB | ASUS P8B75-M LE |
| Audio | VT1708S |
| SSD | Crucial M500 120GB |
| HDD | TOSHIBA DT01ACA200 1TB |
| iGPU |  |
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
| Microphone | Working, but defective | The input sound gets crackled with input volume turned to high level in settings.<br><br>If you are running macOS 11.3+, you will need to drop the VoodooHDA.kext customized for VT1708S to /S/L/E on your own. |
|CFG Lock| Enabled | I have not found any method to disable CFG Lock. So, the power management may be worse than the native ones. |
<br>


## Recommended BIOS Settings
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
- <https://blog.csdn.net/amoscn/article/details/113703944>
- <https://bbs.pcbeta.com/forum.php?mod=viewthread&tid=1862613>
- <https://www.zdynb.cn/2020/jie-suo-cfg-lock.html>
- <https://www.youtube.com/watch?v=uS3X13naPcM>
<br>


## Credits
- [**Apple**](https://www.apple.com/tw/) for the macOS.
- [**Dortania**](https://github.com/dortania) for the great guides.
- [**Acidanthera**](https://github.com/acidanthera) for [AppleALC](https://github.com/acidanthera/AppleALC), [Lilu](https://github.com/acidanthera/Lilu), [OpenCore](https://github.com/acidanthera/OpenCorePkg), [VoodooPS2](https://github.com/acidanthera/VoodooPS2), [VirtualSMC](https://github.com/acidanthera/VirtualSMC), [WhateverGreen](https://github.com/acidanthera/WhateverGreen)
- [**RehabMan**](https://github.com/RehabMan) for [USBInjectAll](https://github.com/RehabMan/OS-X-USB-Inject-All)

# Update 2019/07/23

# Wiki

https://github.com/SuperNG6/MSI-B360-10.14.5-EFI/wiki


# Info

    CPU:i5 8400 GPU:UHD630 SSD:SAM 960PRO SMBIOS:2018 Mac mini
    
    macOS Catalina 10.15 Beta4

    Clover 5027
    
    AppleALC 1.3.9
    
    IntelMausi 1.0.0
    
    Lilu 1.3.7
    
    USBInjectAll 0.7.1
    
    VirtualSMC 1.0.6
    
    WhateverGreen 1.3.0
    

## Changelog

### 2019/07/23

    1、EFI Refactoring
    2、Support macOS Catalina 10.15 Beta4

### 2019/06/23

    1、Update Clover 4969 && Support macOS Catalina Beta2
    2、Update VirtualSMC 1.0.5
    3、Update WhateverGreen 1.3.0
    4、Update Lilu 1.3.7
    5、Update AppleALC 1.3.9
    6、Replace OsxAptioFixDrv-64.efi with OsxAptioFix2Drv-free2000.efi & Enhanced compatibility

### 2019/06/07

    1、Update Clover 4952 && Update USB Patches

### 2019/06/04

    1、Update Clover 4940 && Support macOS Catalina Beta1

### 2019/06/01

    1、Update Clover 4937
    2、Replace IntelMausiEthernet with IntelMausi && Improve network performance and stability
    3、Update VirtualSMC 1.0.4 && remove SMCSuperIO.kext
    4、Update AppleALC 1.3.8 && Lilu 1.3.6 WhateverGreen 1.2.9
    5、Add PCI Devices info && Fix mic

### 2019/05/14

    1、Update Clover 4928 && Update AppleALC 1.3.7
    2、Support macOS Mojave 10.14.5
    
### 2019/05/04

    1、Update Clover 4925
    2、Replace FakeSMC with VirtualSMC
    3、Add SMCProcessor.kext、SMCSuperIO.kext
    4、Remove HibernationFixup.kext
    5、Improve performance and stability

### 2019/04/13

    1、Update Clover 4919 && Support HDMI、DVI
    
### 2019/03/31

    1.Update Clover 4915 fix applertc patch for 10.14.4+. thanks to RodionS
      Cleanup iGPU values and fix force reboot when wakes up with an HDMI connected in 10.14+
    2.Remove ‘Fix RTC _STA bug’ patch

### 2019/03/28

    1、Exclude new framebuffer patchers because of its instability
    2、Do not support HDMI、DVI for the moment

### 2019/03/25
    
    1、Update Clover 4895 Support macOS Mojave 10.14.4
    2、Compatible with the latest BIOS version && Support DP、HDMI、DVI
    3、Update USB Patches
    4、Replace VBoxHfs-64.efi with HFSPlus.efi
    5、Update AppleALC && Lilu && WhateverGreen
    


### 2019/01/25

    1、Fix Audio (Layout ID 15) and use Hackintool driver UHD630
    2、Update Clover version 4862 support macOS 10.14.4 beta1
    3、It is highly recommended to upgrade to the latest version to solve USB problems


    
# Recommend to modify your SMBIOS
Link of tutorial：https://sleele.com/2019/03/21/smbios/
![示例图片加载失败](https://raw.githubusercontent.com/SuperNG6/pic/master/Hackintosh%20images/SMBIOS.png)

### Recommend BIOS version 7B23v16
MSI B360 BIOS download link https://cn.msi.com/Motherboard/support/B360M-MORTAR
![示例图片加载失败](https://raw.githubusercontent.com/SuperNG6/pic/master/Hackintosh%20images/BIOS.png)

### hackintosh PCI Devices setting
Link of tutorial：https://sleele.com/2019/05/05/hackintosh-pcidevices/
![示例图片加载失败](https://raw.githubusercontent.com/SuperNG6/pic/master/Hackintosh%20images/image-14.png)

# Detail:
 [My Blog: sleele.com/2018/12/01/hackintosh/ ](https://sleele.com/2018/12/01/hackintosh/ "Blog")

![示例图片加载失败](https://raw.githubusercontent.com/SuperNG6/pic/master/Hackintosh%20images/image-5.png)
![示例图片加载失败](https://raw.githubusercontent.com/SuperNG6/pic/master/Hackintosh%20images/image-2.png)
![示例图片加载失败](https://raw.githubusercontent.com/SuperNG6/pic/master/Hackintosh%20images/image-8.png)
![示例图片加载失败](https://raw.githubusercontent.com/SuperNG6/pic/master/Hackintosh%20images/image-12.png)
![示例图片加载失败](https://raw.githubusercontent.com/SuperNG6/pic/master/Hackintosh%20images/image-13.png)
![示例图片加载失败](https://raw.githubusercontent.com/SuperNG6/pic/master/Hackintosh%20images/image-6.png)
![示例图片加载失败](https://raw.githubusercontent.com/SuperNG6/pic/master/Hackintosh%20images/image-4.png)
![示例图片加载失败](https://raw.githubusercontent.com/SuperNG6/pic/master/Hackintosh%20images/image-7.png)

# Update 2020/03/14

# Getting Started Tutorials & Documentation
https://sleele.com/2019/07/14/gettingstartedtutorial/

# Wiki

https://github.com/SuperNG6/MSI-B360-Catalina-EFI/wiki

# OpenCore Guide

https://sleele.com/2019/10/31/opencore-guide/

# Download
https://github.com/SuperNG6/MSI-B360-Catalina-EFI/releases


# Info

    CPU:i5 8400 GPU:AMD5500xt UHD630 SSD:SAM 960PRO SMBIOS:2018 Mac mini
    
    Support macOS Catalina or newer

    OpenCorePkg 0.5.6
    
    AppleALC 1.4.7
    
    IntelMausi 1.0.2
    
    Lilu 1.4.2
    
    VirtualSMC 1.1.1
    
    WhateverGreen 1.3.7
    

## Please turn on intel graphics card in the BIOS

## Changelog

### 2020/03/14

    1、Only support AMD 5500xt (UHD630+AMD5500xt)
    2、Highly customizable


    
## If you used to apply simulation nvaram，please operate in the following way.  
### Clover  
````
delete these files
/Volumes/EFI/nvram.plist
/etc/rc.clover.lib
/etc/rc.boot.d/10.save_and_rotate_boot_log.local
/etc/rc.boot.d/20.mount_ESP.local
/etc/rc.boot.d/70.disable_sleep_proxy_client.local.disabled
/etc/rc.boot.d/80.save_nvram_plist.local
/etc/rc.boot.d
/etc/rc.shutdown.d
````

### OpenCore  
````
sudo rm -rf $(sudo defaults read com.apple.loginwindow LogoutHook)
sudo defaults delete com.apple.loginwindow LogoutHook
````




    
# Recommend to modify your SMBIOS
Link of tutorial：https://sleele.com/2019/03/21/smbios/
![vXUITT](https://cdn.jsdelivr.net/gh/SuperNG6/pic@master/uPic/vXUITT.png)

### Recommend BIOS version 7B23v16
MSI B360 BIOS download link https://cn.msi.com/Motherboard/support/B360M-MORTAR
![示例图片加载失败](https://raw.githubusercontent.com/SuperNG6/pic/master/Hackintosh%20images/BIOS.png)

### hackintosh PCI Devices setting
Link of tutorial：https://sleele.com/2019/05/05/hackintosh-pcidevices/
![示例图片加载失败](https://raw.githubusercontent.com/SuperNG6/pic/master/Hackintosh%20images/image-14.png)

# Detail:
 [My Blog: sleele.com/2018/12/01/hackintosh/ ](https://sleele.com/2018/12/01/hackintosh/ "Blog")

![2qtqFu](https://cdn.jsdelivr.net/gh/SuperNG6/pic@master/uPic/2qtqFu.png)
![cKp37i](https://cdn.jsdelivr.net/gh/SuperNG6/pic@master/uPic/cKp37i.png)
![7o6k83](https://cdn.jsdelivr.net/gh/SuperNG6/pic@master/uPic/7o6k83.png)
![示例图片加载失败](https://raw.githubusercontent.com/SuperNG6/pic/master/Hackintosh%20images/image-8.png)
![Zq3EKh](https://cdn.jsdelivr.net/gh/SuperNG6/pic@master/uPic/Zq3EKh.png)
![9vtHF1](https://cdn.jsdelivr.net/gh/SuperNG6/pic@master/uPic/9vtHF1.png)
![vNLdMd](https://cdn.jsdelivr.net/gh/SuperNG6/pic@master/uPic/vNLdMd.png)
![aIzBBu](https://cdn.jsdelivr.net/gh/SuperNG6/pic@master/uPic/aIzBBu.png)

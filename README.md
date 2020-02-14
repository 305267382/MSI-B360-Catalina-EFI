# Update 2020/02/14

# Getting Started Tutorials & Documentation
https://sleele.com/2019/07/14/gettingstartedtutorial/

# Wiki

https://github.com/SuperNG6/MSI-Catalina-EFI/wiki

# Download
https://github.com/SuperNG6/MSI-B360-Catalina-EFI/releases

# OpenCore Guide

https://sleele.com/2019/10/31/opencore-guide/

# Info

    
    Support macOS Mojave or newer

    OpenCorePkg 0.5.5
    
    AppleALC 1.4.6
    
    IntelMausi 1.0.2
    
    Lilu 1.4.1
    
    VirtualSMC 1.1.1
    
    WhateverGreen 1.3.6
    
## Changelog

### 2020/02/14

    1、update OpenCorePkg 0.5.5 & AppleALC 1.4.6 & VirtualSMC 1.1.1
    2、remove slide value,now support more Motherboard (z390,b360 b365 ....)
    3、support native nvram for 300-series chipsets
    4、added TakeoffDelay value(200) for improved action hotkey support
    5、support macOS Catalina 10.15.3

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

### 2020/01/15

    1、remove ThirdPartyTrim item
    2、remove VirtualSMC.efi (opencore built in)
    3、update opencore & driver & kext
    4、minor performance improvements
    5、improve PowerManagement
    5、Support macOS Catalina 10.15.2

### 2019/11/19

    1、Fix:OCS: Failed to parse string field of type 2

### 2019/11/18

    1、Delete EmuVariableRuntimeDxe.efi

### 2019/11/01

    1、EFI Refactoring
    2、Support macOS Catalina 10.15.1
    3、Update Kexts and driver

### 2019/08/11

    1、Apply OpenCore to build
    2、Update Kexts and Drivers to the latest version
    3、Support more hardwares (enhance compatibility)
    4、Support macOS Mojave or newer
    5、Faster boot speed
    6、Remove redundant files
    7、Customized USBPorts
  

# Detail
![](https://github.com/SuperNG6/pic/blob/master/OpenCore/Xnip2019-11-01_19-37-52.png)
![](https://github.com/SuperNG6/pic/blob/master/OpenCore/Xnip2019-11-01_19-37-58.png)
![](https://github.com/SuperNG6/pic/blob/master/OpenCore/Xnip2019-11-01_19-41-00.png)
![](https://github.com/SuperNG6/pic/blob/master/OpenCore/Xnip2019-11-01_19-13-51.png)
![](https://github.com/SuperNG6/pic/blob/master/OpenCore/Xnip2019-11-01_19-15-25.png)



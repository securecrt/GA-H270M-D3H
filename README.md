# GIGABYTE GA-H270M-D3H

OpenCore EFI for Gigabyte GA-H270M-D3H


```text
                    'c.          iMac
                 ,xNMM.          -------------------- 
               .OMMMMo           OS: macOS 13.2.1 22D68 x86_64 
               OMMM0,            Host: Hackintosh (SMBIOS: iMac18,2) 
     .;loddo:' loolloddol;.      Kernel: 22.3.0 
   cKMMMMMMMMMMNWMMMMMMMMMM0:    Uptime: 1 hour, 2 mins 
 .KMMMMMMMMMMMMMMMMMMMMMMMWd.    Packages: 93 (brew) 
 XMMMMMMMMMMMMMMMMMMMMMMMX.      Shell: bash 5.2.15 
;MMMMMMMMMMMMMMMMMMMMMMMM:       Resolution: 2560x1440@2x 
:MMMMMMMMMMMMMMMMMMMMMMMM:       DE: Aqua 
.MMMMMMMMMMMMMMMMMMMMMMMMX.      WM: Quartz Compositor 
 kMMMMMMMMMMMMMMMMMMMMMMMMWd.    WM Theme: Blue (Dark) 
 .XMMMMMMMMMMMMMMMMMMMMMMMMMMk   Terminal: Apple_Terminal 
  .XMMMMMMMMMMMMMMMMMMMMMMMMK.   Terminal Font: SFMono-Regular 
    kMMMMMMMMMMMMMMMMMMMMMMd     CPU: Intel i7-7700 (8) @ 3.60GHz 
     ;KMMMMMMMWXXWMMMMMMMk.      GPU: AMD Radeon RX 6600 XT 
       .cooc,.    .,coo:.        Memory: 11318MiB / 32768MiB 
```

### OpenCore 
* **Version:** 0.9.0

### Hardware

* **MOBO:** Gigabyte GA-H270M-D3H
* **RAM:** Kingston DDR4-2400 32GB (4x8GB)
* **CPU:** Intel Core i7-7700
* **GPU:** AMD Radeon RX 6600 XT
* **WIFI/BT:** BCM934602CS
* **SSD:** Samsung SSD 970 EVO 1TB


### BIOS Settings

* Settings
	* M.I.T.
		*  Advanced Memory Settings
			*  Extreme Memory Profile(X.M.P.) → **Profile1**
	* BIOS
		*  Fast Boot → **Disabled**
		*  Windows 8/10 Features → **Windows 8/10**
		*  CSM Support → **Disabled**
	* Peripherals
		* Initial Display Output → **iGFX**
		* Intel Platform Trust Technology (PTT) → **Enabled**
		* Super IO Configuration
			* Serial Port → **Disabled** 
		* USB Configuration
			* XHCI Hand-off → **Enabled**
	* Chipset
		* VT-d → **Enabled**      
		* DVMT Pre-Allocated → **64M**

### Not working
None

### macOS Support
| Version   | macOS | Download |
| --------: | :---- | :------- |
| 13.2.1 | Ventura | [Mac App Store](https://apps.apple.com/us/app/macos-ventura/id1638787999?mt=12) |
# GIGABYTE GA-H270M-D3H

OpenCore EFI for Gigabyte GA-H270M-D3H

![about](https://raw.githubusercontent.com/securecrt/GA-H270M-D3H/master/about.png)


### OpenCore 
* **Version:** 0.9.0

### Hardware

* **MOBO:** Gigabyte GA-H270M-D3H
* **RAM:** Kingston DDR4-2400 32GB (4x8GB)
* **CPU:** Intel Core i7-7700
* **GPU:** Intel HD Graphics 630
* **dGPU:** Nvidia Gefore 1050 Ti
* **SSD:** Samsung SSD 970 EVO 1TB

### BIOS Settings

* Settings
	* M.I.T.
		*  Advanced Memory Settings
			*  Extreme Memory Profile(X.M.P.) → **Profile1**
	*  BIOS
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
		* VT-d → **Disabled**      
		* DVMT Pre-Allocated → **64M**

### Issues
* dGPU not working
* Wifi (ax200) is not stable
* Bluetooth can't work
* Hibernation

### macOS Support
| Version   | macOS | Download |
| --------: | :---- | :------- |
| 13.2.1 | Ventura | [Mac App Store](https://apps.apple.com/us/app/macos-ventura/id1638787999?mt=12) |
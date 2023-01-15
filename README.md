# TUF-GAMING-B460M-Plus-OpenCore-Hackintosh
OpenCore 0.8.7 for TUF B460M that has been tested to work from Catalina to Ventura

![Ventura Screenshot](https://raw.githubusercontent.com/nemorosus/TUF-GAMING-B460M-Plus-OpenCore-Hackintosh/main/Screenshot.png)

###  :mag_right: Specifications 

| Part        | Specs                                             |
| ----------- | ------------------------------------------------- |
| CPU         | Intel® Core™ i5-10400F                            |
| iGPU        | N/A                                               |
| dGPU        | AMD RX580 8GB (ASUS DUAL-RX580-O8G)               |
| Audio       | Realtek S1200A                                    |
| Ethernet    | Intel® I219-V LAN                                 |
| Motherboard | ASUS TUF Gaming B460M Plus with latest BIOS |

### :bulb: ​Working/Not working

| Works              | Feature                                               |
| ------------------ | ----------------------------------------------------- |
| :white_check_mark: | Native power management  |
| :white_check_mark: | Sound (output+inputs)                                 |
| :white_check_mark: | USB 2.0 and 3.0 - all ports                              |
| :white_check_mark: | AMD RX580 Full Graphics Acelleration                    |
| :white_check_mark: | Sleep (also with peripherals plugged in)              |
| :white_check_mark: | Ethernet                                              |
| :white_check_mark: | iCloud, FaceTime, etc.                                          |

This is a fork of this [MSI B460M PRO](https://addrom.com/efi-msi-b460m-pro-intel-i5-10400-amd-rx470-and-macos-ventura/) configuration, with slight adjustments to work with the TUF motherboard.

⚠️ The versions with Wi-Fi & Bluetooth are more common, but it generally is the same thing just with few patches for those chips to work. As that motherboard is much more popular than what I have without, you can browse through other repositories here and see what and how they patched the hardware to work, but I reckon is pretty easy because I've seen those confirmed to work just fine.

###  ℹ ​Installation Notes
* [Check Dortania's guide](https://dortania.github.io/OpenCore-Install-Guide/) for the detailed guide on all parts
* Generate correct serial numbers and replace the "XXXX" placeholders in the config.plist
* If you are using supported AMD card, you should have full hardware acelleration by default with this configuration
* If you use another processor with iGPU, there might be some tweaks you will need to do by yourself

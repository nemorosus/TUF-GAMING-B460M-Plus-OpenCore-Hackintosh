# TUF-GAMING-B460M-Plus-OpenCore-Hackintosh
![new_bgr_0 9 9](https://github.com/nemorosus/TUF-GAMING-B460M-Plus-OpenCore-Hackintosh/assets/6278519/ebcdddf9-e2aa-423d-ad79-542a30c74caa)

![Screenshot 2024-03-18 at 19 17 59](https://github.com/nemorosus/TUF-GAMING-B460M-Plus-OpenCore-Hackintosh/assets/6278519/f60b23e6-14da-4ea9-84fd-34a6e66ac4fd)


###  :mag_right: 👾 Specifications 

| Part        | Specs                                             |
| ----------- | ------------------------------------------------- |
| CPU         | Intel® Core™ i5-10400F                            |
| iGPU        | N/A                                               |
| dGPU        | AMD RX580 8GB (ASUS DUAL-RX580-O8G)               |
| Audio       | Realtek S1200A                                    |
| Ethernet    | Intel® I219-V LAN                                 |
| Wi-Fi       | Broadcom BCM4360                                  |
| Bluetooth   | Broadcom BRCM20702                                |
| Motherboard | ASUS TUF Gaming B460M Plus with latest BIOS |

### :bulb: ​👌

| Works              | Feature                                               |
| ------------------ | ----------------------------------------------------- |
| :white_check_mark: | Native power management                               |
| :white_check_mark: | Sound (output+inputs)                                 |
| :white_check_mark: | USB 2.0 and 3.0 - all ports                           |
| :white_check_mark: | AMD RX580 Full Hardware Decoder + DRM                 |
| :white_check_mark: | Sleep (also with peripherals plugged in)              |
| :white_check_mark: | Ethernet, Bluetooth, Wi-Fi (⋆)                        |
| :white_check_mark: | iCloud, FaceTime, AirDrop, etc.                       |
| :white_check_mark: | FileVault                                             |

⚠️ For Wi-Fi, you need to apply OCP root wireless patches. Also, for best security please consider constricting the configuration and modify it towards your goals, as at it current state its very open and only recommended for people who know what they're doing.

###  💿 ​Installation Notes
* Download the latest in Releases > And start there with the read-me!
* [Check Dortania's guide](https://dortania.github.io/OpenCore-Install-Guide/) for the detailed guide on all parts
* Generate correct serial numbers and replace the "XXXX" placeholders in the config.plist
* If you are using supported AMD card, you should have full hardware acelleration by default with this configuration
* If you use another processor with iGPU, there might be some tweaks you will need to do by yourself

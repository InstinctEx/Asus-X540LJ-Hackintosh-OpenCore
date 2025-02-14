# Asus-X540LJ-Hackintosh-OpenCore
Asus X540LJ Hackintosh working OpenCore 0.7.0 EFI with macOS Big Sur 11.4

# Asus Vivobook X540LJ
- **Bootloader:** OpenCore 0.7.0
- **macOS:** 11.4 Big Sur

# Changelog
### Update: 8-June-2021
- OpenCore Update 0.6.8 to 0.7.0
- Bluetooth Kext Update
- Ethernet Kext Update
- Android USB Tethering Kext Update
- BIOS config changes

### Update: 11-April-2021
- Updated OpenCore 0.6.7 to 0.6.8
- Updated some Kext

### Update: 30-March-2021
- Bluetooth has been fixed
- Realtek SD Card Reader Fixed
- Realtek Ethernet Fixed

# Specification:

- **MainBoard:** Asus X540LJ.
- **Processor:** Intel Core i3-5005U @ 2.0GHz (Broadwell)
- **RAM:** 8GB DDR3 1600mhz (Duel channel)
- **Graphic:** 
  + Intel HD5500
  + NVIDIA GeForce 920M 2GB
- **Network:**
  + **Wifi:** Atheros AR9565
  + **Ethernet:** Realtek RTL810xE
- **Audio:** Realtek ALC255 (layout-27)
- **Touchpad:** ELAN 1100 (I2C)
- **SD Card Reader** Realtek RTS5286
- **Storage**: 240GB SSD, 1TB HDD

# WORKING:
- [x] Power Management
- [x] Intel HD Graphics 5500
- [x] Sound **(Internal Speaker and Headphone working)**
- [x] Mic **(Internal and External both working)**
- [x] Wifi
- [x] Bluetooth
- [x] SD Card Reader
- [x] Ethernet
- [x] Adjust brightness 
- [x] USB 2.0 and 3.0
- [x] Trackpad **(All gestures supported)**
- [x] Sleep  **(working while power adapter is not connected and using battery)**
- [x] Battery Stat 
- [x] Tempareture Monitor 
- [x] Apple Store 
- [x] iCloud 
- [x] Fn feature    **(not all button works)**

# Not WORKING:
- [ ] Nvidia 920M GPU   **(will never work)**


# BIOS Settings:
- No need to change any BIOS settings. Set default BIOS settings.
- If you use secondery monitor then disable **Launch CSM** in BIOS boot section.


# Installation:
- Change the default BIOS settings.
- Just put this EFI to your USB EFI partition.
- Install macOS Big Sur.
- No need to install any additional kext to macOS extention. All driver will be loaded automatically.
- After install mount the USB EFI and copy this to your HDD EFI.
- Change the serial numbers and other things. You can find the tutorial from [here.](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/broadwell.html#platforminfo)

# Bluetooth fix:
- To toggle on/off bluetooth, you have to swichoff your wifi.


## Credits
@RehabMan for his guide for beginner
@alexandred and his team for VoodooI2C 
@acidanthera for his OpenCore Bootloader and kexts
@zxystd for Atheros Bluetooth fix
and many more people that I can't list here.

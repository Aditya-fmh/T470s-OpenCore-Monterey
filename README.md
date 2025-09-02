# Hackintosh Monterey on Lenovo ThinkPad T470s

This repository contains the EFI and guide for running **macOS Monterey** on the **Lenovo ThinkPad T470s**.  
Tested and working on the following configuration:

## Hardware Specifications

| Component            | Details                     |
|----------------------|-----------------------------|
| Laptop Model         | Lenovo ThinkPad T470s       |
| CPU                  | Intel Core i7-7600U (Kaby Lake) |
| RAM                  | 8 GB DDR4                   |
| Storage              | 256 GB SATA SSD             |
| iGPU                 | Intel HD Graphics 620       |
| Display              | 14" FHD (1920x1080)         |
| Wi-Fi & Bluetooth    | Intel Wi-Fi & Bluetooth |
| Audio                | Realtek ALC298 (T470s stock) |
| Ethernet             | Intel I219-LM               |
| Touchpad / Trackpoint | Synaptics PS/2 |

---

## macOS Version

- **Monterey (12)**

---

## What's Working ✅

- [x] Intel HD Graphics 620 with full acceleration  
- [x] Keyboard & TrackPoint / Trackpad with gestures  
- [x] Audio (Internal speakers, mic, headphone jack)  
- [x] USB ports (mapped)  
- [x] Ethernet  
- [x] Sleep & Wake  
- [x] Battery status  
- [x] Brightness controls  
- [x] Camera   

---

## Not Working / Issues / Untested ⚠️

- [ ] Fingerprint reader (no fingerprint reader on my laptop)  
- [ ] SD Card reader (untested)  
- [ ] HDMI audio (untested)  
- [ ] External monitor (untested)  

---

## Installation Notes

- Created installer with [OpenCore](https://dortania.github.io/OpenCore-Install-Guide/).  
- SMBIOS used: **MacBookPro14,1**
- Recommended BIOS settings:
  - Disable Secure Boot  
  - Disable Fast Boot  
  - SATA mode: AHCI  
  - Enable UEFI boot  

---

## Credits

- [Acidanthera](https://github.com/acidanthera) for OpenCore and kexts  
- [Dortania Guides](https://dortania.github.io/) for detailed documentation  
- Hackintosh community for support and patches  

---

## Disclaimer

This EFI is shared **for educational purposes only**.  
Please use it at your own risk. I am not responsible for any damage or data loss caused by using this setup.

# OpenCore EFI for Ryzen 3600 &amp; MSI B450I Gaming Plus AC

## Thanks to [OepnCore Vanilla Desktop Guide](https://khronokernel-2.gitbook.io/opencore-vanilla-desktop-guide/amd-config.plist/amd-config)
## HW Builds

| Type                 | Name                     |
|----------------------|--------------------------|
| CPU                  | Ryzen 3600               |
| MB                   | MSI B450I Gaming Plus AC |
| Audio                | ALC887                   |
| GPU                  | Radeon RX 5500XT 8 GB    |
| RAM                  | 32G DDR4 (16G * 2)       |
| Wireless & Bluetooth | DW1560                   |

## Functional

- [x] CPU by [AMD-Vanilla](https://github.com/AMD-OSX/AMD_Vanilla)
- [x] USB by [Opencore-Vanilla-Desktop-Guide](https://github.com/khronokernel/Opencore-Vanilla-Desktop-Guide/blob/master/AMD/AMD-USB-map.md)
- [x] Audio by [AppleALC](https://github.com/acidanthera/AppleALC) (alcid=7)
- [x] Graphics by [WhateverGreen](https://github.com/acidanthera/WhateverGreen)
- [x] WIFI by [AirportBrcmFixup](https://github.com/acidanthera/AirportBrcmFixup) (brcmfx-country=#a)
- [x] Bluetooth by [BrcmPatchRAM](https://github.com/RehabMan/OS-X-BrcmPatchRAM)
- [x] iMessage / FaceTime / Airdrop / Handoff

## Notice

- **Please generator your own SMBIOS using [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)**.
- If you are using Adobe software, please refer to this article [Adobe fix](https://kb.amd-osx.com/guides/adobe).

## Issues

- Wrong ram speed display in About This Mac (shows half speed)
- No 32-bit support
- Can't run andriod emulator since android emulator only supports vt-x, but genymotion and virtualbox with amd-v support work well

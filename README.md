# OpenCore EFI for Ryzen 3600 &amp; MSI B450I Gaming Plus AC

Thanks to [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)

## HW Builds

<table>
<tr>
  <th>Type</th>
  <th>Name</th>
  <th></th>
</tr>
  <tr>
    <td>CPU</td>
    <td>AMD Ryzen 3600</td>
    <td rowspan="6"><img width="200" src="/screenshot/screenshot.png"></td>
  </tr>
  <tr>
    <td>Motherboard</td>
    <td>MSI B450I Gaming Plus AC</td>
  </tr>
  <tr>
    <td>Audio</td>
    <td>ALC887</td>
  </tr>
  <tr>
    <td>GPU</td>
    <td>Radeon RX 5500XT 8GB</td>
  </tr>
  <tr>
    <td>RAM</td>
    <td>32G DDR4 (16G * 2)</td>
  </tr>
  <tr>
    <td>Wireless &amp; Bluetooth</td>
    <td>Wireless-AC 9260</td>
  </tr>
</table>

## Functional

- [x] CPU by [AMD-Vanilla](https://github.com/AMD-OSX/AMD_Vanilla)
- [x] USB by [USBToolBox](https://github.com/USBToolBox/tool)
- [x] Audio by [AppleALC](https://github.com/acidanthera/AppleALC) (alcid=6)
- [x] Graphics by [WhateverGreen](https://github.com/acidanthera/WhateverGreen)
- [x] WIFI by [itlwm](https://openintelwireless.github.io/itlwm/)
- [x] Bluetooth by [IntelBluetoothFirmware](https://openintelwireless.github.io/IntelBluetoothFirmware/)

## Notice

- **Please generator your own SMBIOS using [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)**.

## Issues

- Wrong ram speed display in About This Mac (shows half speed)
- No 32-bit support
- Can't run andriod emulator since android emulator only supports vt-x, but genymotion and virtualbox with amd-v support work well
- Onboard microphone port not work
- Airdrop / Handoff not work due to Intel bluetooth
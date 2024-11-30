# Huawei MateBook D13 AMD Hackintosh EFI

## Introduction

This repository contains the necessary files to run macOS on the Huawei MateBook D13 laptop. This EFI configuration is created for [OpenCore](https://github.com/acidanthera/OpenCorePkg) bootloader.

!!! I AM NOT RESPONSIBLE FOR ANY DAMAGE THAT CAN OCCUR ON YOUR PERSONAL DEVICE !!!



## Hardware Compatibility

- **Laptop Model:** Huawei MateBook D13
- **Processor:** Processor	AMD Ryzen 5 3500U
- **Graphics:** AMD Radeon(TM) Vega 8 Graphics
- **Wireless Card:** Realtek 8822CE [DOESN'T WORK]
- **Audio:** Realtek ALC256 [NO INPUT, ONLY OUTPUT]
- **Trackpad:** ELAN I2C/HID Trackpad

## Features

- **Full QE/CI and Metal Support:** The Vega GPU is supported enough for daily use.
- **Audio:** Audio output works but, no input loool
- **Trackpad and Keyboard:** Trackpad and Keyboard is fully supported.
- **Power Management:** Sleep, wake is working. The battery life is poor.

## Working Devices

- [x] **Keyboard:** Fully working with shortcut buttons.
- [x] **Trackpad:** Fully working with multiple gestures.
- [x] **Speakers:** Works well.
- [x] **Display:** Brightness is adjustable.
- [x] **Video output through USB-C:** Impressive!
- [x] **Audio Jack:** Audio is supported.

## Non-Working Devices

- [ ] **Wifi:** No support for the wireless card.
- [ ] **Bluetooth:** No support for the wireless card.
- [ ] **Microphone:** Might be fixable (needs further investigation).
- [ ] **Fingerprint Sensor:** No support.

## Prerequisites

- Huawei MateBook D13
- An EFI Partition (Can be on your USB Drive or a divided partition of any disk on computer. Anything from 150MB-500MB)
- A brain (optional)

## Installation Steps

1. **Download the EFI Files:**
   Clone this repository or download the ZIP file. Extract the contents to somewhere.

2. **Copy the EFI Files:**
   Copy the EFI Folder. Your EFI drive should look like this: "X:/EFI"

3. **Register the EFI File to your BIOS:**
   Uhh yeah.

4. **Boot MacOS:**
   Congrats.

## Credits

Give credit to the developers and contributors whose work made this Hackintosh possible.

- [OpenCore Team](https://github.com/acidanthera/OpenCorePkg)
- My dad

## Disclaimer

This EFI configuration is provided as-is and without any warranty. Use it at your own risk. The developers and contributors are not responsible for any damage to your hardware or data.

## Contributing

Feel free to contribute by opening issues, submitting pull requests, or sharing your experiences with this Hackintosh configuration.

Happy Hacking!

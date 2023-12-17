# Huawei MateBook D13 AMD Hackintosh EFI

## Introduction

This repository contains the necessary files to run macOS on the Huawei MateBook D13 laptop. This EFI configuration is created for [OpenCore](https://github.com/acidanthera/OpenCorePkg) bootloader.

!!! I AM NOT RESPONSIBLE FOR ANY DAMAGE TO YOUR COMPUTER MINE RUNS FINE FOR NOW LOL !!!


## Hardware Compatibility

- **Laptop Model:** Huawei MateBook D13
- **Processor:** Processor	AMD Ryzen 5 3500U
- **Graphics:** AMD Radeon(TM) Vega 8 Graphics
- **Wireless Card:** Realtek 8822CE [NO WORKIES]
- **Audio:** Realtek ALC256 [NO INPUT]
- **Trackpad:** ELAN POOP

## Features

- **Full QE/CI and Metal Support:** The Vega GPU is supported enough for daily use.
- **Audio:** Audio output works but, no input loool
- **Trackpad and Keyboard:** Trackpad and Keyboard is fully supported.
- **Power Management:** Sleep, wake is working.

## Working Devices

- [✓] **Keyboard:** Fully working with shortcut buttons.
- [✓] **Trackpad:** Fully working with multiple gestures.
- [✓] **Speakers:** Works well.
- [✓] **Display:** Brightness is adjustable.
- [✓] **Video output through USB-C:** Impressive!
- [✓] **Audio Jack:** Audio is supported.

## Non-Working Devices

- [x] **Wifi:** No support for the wireless card.
- [x] **Bluetooth:** No support for the wireless card.
- [x] **Microphone:** Might be fixable (needs further investigation).
- [x] **Fingerprint Sensor:** No support.

## Prerequisites

- Huawei MateBook D13
- An EFI Partition (Can be on your USB Drive or a divided partition of any disk on computer. Anything from 150MB-500MB)
- A Brain

## Installation Steps

1. **Download the EFI Files:**
   Clone this repository or download the ZIP file. Extract the contents to the EFI partition of your USB drive.

2. **Copy the EFI Files:**
   Copy the EFI Files. Your EFI drive should look like this: "X:/EFI"

3. **Register the EFI File to your BIOS:**
   Uhh yeah.

4. **Boot MacOS:**
   omg!!! :3

## Credits

Give credit to the developers and contributors whose work made this Hackintosh possible.

- [OpenCore Team](https://github.com/acidanthera/OpenCorePkg)
- My dad

## Disclaimer

This EFI configuration is provided as-is and without any warranty. Use it at your own risk. The developers and contributors are not responsible for any damage to your hardware or data.

## Contributing

Feel free to contribute by opening issues, submitting pull requests, or sharing your experiences with this Hackintosh configuration.

Happy Hacking!

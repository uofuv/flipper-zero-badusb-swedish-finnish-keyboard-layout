# Flipper Zero release 0.100.3
Flipper Zero release 0.100.3 - Updated furi_hal_usb_hid.h for BadUSB to work with swedish and finnish keyboard layouts


#### Compile it yourself
1. `git clone https://github.com/uofuv/flipper-zero-badusb-swedish-finnish-keyboard-layout.git`
2. `git clone --recursive https://github.com/flipperdevices/flipperzero-firmware.git`
3. `cp flipper-zero-badusb-swedish-finnish-keyboard-layout/furi_hal_usb_hid.h flipperzero-firmware/targets/furi_hal_include/furi_hal_usb_hid.h`
4. `cd flipperzero-firmware`
5. compile it with `./fbt` 
6. new firmware binaries / .dfu file can be found at `build/`
7. Flash! 


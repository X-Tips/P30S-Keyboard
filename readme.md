X.Tips P30 Keyboard

Keyboard Maintainer: X.Tips
URL: www.umux.com

2 modes go to bootloader:
The Bootmagic is enable, To go to bootloader press and hold the key in the top left corner while plugging in. If you edit the fireware, please keep the bootmagic feature or set a QK_BOOTLOADER keycode in your keymap file. It can put the keyboard into bootloader mode for flashing.
Short-circuit the BOOT pins on the PCB, then connect this keyboard to the computer.

Flash firmware:
Download and install QMK Toolbox: https://github.com/qmk/qmk_toolbox/releases
Open QMK Toolbox: Load the firmware file (*.bin) and select Auto-Flash.
Press and hold the Q key while plugging the keyboard in PC, QMK Toolbox will automatically detect the DFU device and begin flashing.

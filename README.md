# Firmware for the Creality Ender 3 Pro
## marlin-2.1.2-ender-3-pro-4.2.2-bltouch-pin-27-adapter-board.bin
I could not get the firmware from the Creality website to work. Settings like Z-offset would not save and many times the SD-card would not be recognised.<br><br>After hours of searching for firmware that works, I decided to complile my own firmware. This is based on Marlin 2.1.2, with the default configuration for Creality v4.x boards, and pin 27 adapter board enabled (for BLTouch). Settings save to EEPROM instead of SD-card.

- Creality version 4.2.2 mainboard
- GD32F303RET6 CPU (512K), should also work for STM32F103RET6 
- Bltouch Z-probe (connected on pin 27 adapter board/Z-min)

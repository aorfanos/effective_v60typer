# Effective V60 Type R Keyset

- Typing layer
- Movement layer
- Layer1-Esc acts as **power button**
- other minor tweaks
- WASD keys function as mouse (layer1)
- Q is mouse button 1 (left click)
- E is mouse button 2 (right click)
- ZXC regulate speed of cursor (from lowest to highest)
- [ move up
- ; move left
- ' move right
- / move down

TODO: Implement useful macros, backlight and media control keys, add DVORAK layout layer.

For full layout info (and a visual guide), just import the json file into [QMK Configurator](https://config.qmk.fm/#/v60_type_r/LAYOUT_60_ansi)

## Prerequisites

dfu-bootloader

qmk (optional)

## How to flash 

Press reset button at the bottom and then:

```bash
sudo dfu-bootloader atmega32u4 erase
sudo dfu-bootloader atmega32u4 flash effective_typerv60.hex
sudo dfu-bootloader atmega32u4 start
```

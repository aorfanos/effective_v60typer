# Effective V60 Type R Keyset

- Typing layer
- Movement layer
- Layer1-Esc acts as **power button**
- other minor tweaks

For full layout info, just import the json file into [QMK Configurator](https://config.qmk.fm/#/v60_type_r/LAYOUT_60_ansi)

## Prerequisites

dfu-bootloader
qmk (optional)

## How to flash 

Press reset button at the bottom and then:

```bash
sudo dfu-bootloader atmega32u4 erase
sudo dfu-bootloader atmega32u4 flash <myfirmware>.hex
sudo dfu-bootloader atmega32u4 start
```

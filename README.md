# keyboard_layouts
Layouts for my many keyboards

# GH60

Use EasyAVR [here](https://github.com/dhowland/EasyAVR/)
* File > Open Layout custom.dat
* Press reset button on bottom of pcb, or SC_BOOTMODE button
* File > Build and reprogram

# Zeal60

Setup keymap with [QMK Configurator](https://config.qmk.fm/)
 * Compile
 * Download firmware
 
## Windows or macOS

Flash with [QMK toolbox](https://qmk.fm/toolbox/)

## Linux

Flash with [dfu-programmer](https://github.com/dfu-programmer/dfu-programmer/)

1. Run the following command
2. Put your keyboard into boot mode before the sleep is up

```bash
sleep 3; dfu-programmer atmega32u4 erase; dfu-programmer atmega32u4 flash wilba_tech_zeal60_linux.hex
```

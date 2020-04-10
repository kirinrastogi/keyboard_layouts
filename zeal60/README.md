### Flashing to an atmega32u4 on Windows or macOS

Use [qmk_toolbox](https://github.com/qmk/qmk_toolbox)

### Flashing to an atmega32u4 on Linux

Use [dfu-programmer](https://github.com/dfu-programmer/dfu-programmer)

1. Run the following command
2. Put your keyboard into boot mode before the sleep is up
3. You are done

```bash
sleep 3; dfu-programmer atmega32u4 erase; dfu-programmer atmega32u4 flash wilba_tech_zeal60_linux.hex
```

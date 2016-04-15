# Arduino


- [Use Arduino IDE to develop STM32 MCU (e.g. RedBear Duo) Firmware](https://github.com/redbear/STM32-Arduino)

```sh
$ sudo nano /etc/udev/rules.d/77-mm-usb-device-blacklist.rules
ATTR{idVendor}=="2b04", ENV{ID_MM_DEVICE_IGNORE}="1"
```

> Arduino IDE > File > Preferences > "Additional Boards Manager URLs"
> > https://redbearlab.github.io/arduino/package_redbear_index.json

> Tools > Board > Boards Manager
> > RedBear Duo



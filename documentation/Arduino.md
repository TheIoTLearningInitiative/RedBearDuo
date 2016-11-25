# Arduino

- [Use Arduino IDE to develop STM32 MCU (e.g. RedBear Duo) Firmware](https://github.com/redbear/STM32-Arduino)

```sh
xe1gyq@jessie:~$ sudo nano /etc/udev/rules.d/77-mm-usb-device-blacklist.rules
ATTR{idVendor}=="2b04", ENV{ID_MM_DEVICE_IGNORE}="1"
xe1gyq@jessie:~$ dmesg
[ 2624.128030] usb 5-1: new full-speed USB device number 18 using uhci_hcd
[ 2624.314613] usb 5-1: New USB device found, idVendor=2b04, idProduct=c058
[ 2624.314618] usb 5-1: New USB device strings: Mfr=1, Product=2, SerialNumber=3
[ 2624.314620] usb 5-1: Product: Duo with WiFi and BLE
[ 2624.314623] usb 5-1: Manufacturer: RedBear
[ 2624.314625] usb 5-1: SerialNumber: 00000000050C
[ 2624.318680] cdc_acm 5-1:1.0: This device cannot do calls on its own. It is not a modem.
[ 2624.318702] cdc_acm 5-1:1.0: ttyACM10: USB ACM device

```

> Arduino IDE > File > Preferences > "Additional Boards Manager URLs"
> > https://redbearlab.github.io/arduino/package_redbear_index.json

> Tools > Board > Boards Manager
> > RedBear Duo



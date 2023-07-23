# PyFTDI ESPTOOL Fork

Using pyftdi as serial provider to allow using CBUS gpio.

Tested on Windows with [libusb-win32](https://sourceforge.net/projects/libusb-win32/files/libusb-win32-releases/), once configred FT232RL devices will be listed by serial number. Can also be listed with _testlibusb-win.exe_.

The CBUS gpio is used to control output enable of buffers between esp32 and ftdi.

# esptool.py

A Python-based, open-source, platform-independent utility to communicate with the ROM bootloader in Espressif chips.

[![Test esptool](https://github.com/espressif/esptool/actions/workflows/test_esptool.yml/badge.svg?branch=master)](https://github.com/espressif/esptool/actions/workflows/test_esptool.yml) [![Build esptool](https://github.com/espressif/esptool/actions/workflows/build_esptool.yml/badge.svg?branch=master)](https://github.com/espressif/esptool/actions/workflows/build_esptool.yml)

## Documentation

Visit the [documentation](https://docs.espressif.com/projects/esptool/) or run `esptool.py -h`.

## Contribute

If you're interested in contributing to esptool.py, please check the [contributions guide](https://docs.espressif.com/projects/esptool/en/latest/contributing.html).

## About

esptool.py was initially created by Fredrik Ahlberg (@[themadinventor](https://github.com/themadinventor/)), and later maintained by Angus Gratton (@[projectgus](https://github.com/projectgus/)). It is now supported by Espressif Systems. It has also received improvements from many members of the community.

## License

This document and the attached source code are released as Free Software under GNU General Public License Version 2 or later. See the accompanying [LICENSE file](https://github.com/espressif/esptool/blob/master/LICENSE) for a copy.

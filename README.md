## Overview

`bakebit-nanohat-driver` is a Python I2C driver, with very simple command line interface, for BakeBit NanoHat devices. Currently it supports only the OLED display part.

## Usage

Command line interface for OLED part includes 3 simple scripts:
- `clear.py` - reset the device, set into text mode and clear all contents
- `line.py` - print a single text line
- `restore.py` - print all 8 text lines at once

## Installing

This driver is meant to be used only on Ubuntu 16.04 LTS FriendlyELEC, as provided by NanoPi board vendor. This Ubuntu flavour has certain packages already installed, eg. `python-smbus`. So you only need to download or clone this repository.

You can find more about BakeBit NanoHat OLED devices [here](http://wiki.friendlyarm.com/wiki/index.php/NanoHat_OLED). Note: these devices contain also 3 buttons. These buttons are not supported yet.

## Compatibility

I've tested BakeBit NanoHat OLED devices with NanoPi-NEO2, on dedicated, preinstalled version of Ubuntu 16.04 LTS. It should however work with most NanoPi NEO board models.

## License

BakeBit: an open source platform for connecting BakeBit Sensors to the NanoPi NEO.

|                      |                                          |
|:---------------------|:-----------------------------------------|
| **Author:**          | Tomasz Klim (<opensource@tomaszklim.pl>) |
| **Copyright:**       | Copyright 2016 FriendlyARM (driver)      |
| **Copyright:**       | Copyright 2020 Tomasz Klim (interface)   |
| **License:**         | MIT                                      |

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

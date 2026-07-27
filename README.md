# Munbyn ITPP941P Linux CUPS Driver

Modern Linux CUPS driver for the Munbyn ITPP941P thermal label printer.

Tested on:
- Linux Mint 22.x
- Ubuntu 24.04
- CUPS 2.4.x

## Installation

    git clone https://github.com/AtomicRobotMan0101/Munbyn-Linux-Driver.git
    cd Munbyn-Linux-Driver
    sudo ./install

Then add the printer:

    http://localhost:631

Choose:
    Munbyn ITPP941P

## Files

rastertolabeltspl
    CUPS raster filter converting CUPS raster output to TSPL

Munbyn-ITPP941P.ppd
    Printer definition

## Notes

The supplied filter binary is x86_64 Linux.

## THANKS

Thanks goes to everyone before me that gave hints as to how this internet relic works.

https://forums.freebsd.org/threads/print-beeprt-label-printer-cups-driver.80299/
https://www.beeprt.com/download/drivers/2.html
https://forum.manjaro.org/t/munbyn-itpp941-stopped-no-available-printer/114284
https://drive.google.com/drive/folders/1RovQ-Cr1pb36OcfGu5O9603DJ-jZFgll (avoid this nightmare file. Its a MESS).


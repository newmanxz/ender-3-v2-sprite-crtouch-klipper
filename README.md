# ender-3-v2-sprite-crtouch-klipper

From:

https://github.com/Klipper3d/klipper

https://github.com/Klipper3d/klipper/blob/master/config/printer-creality-ender3-2018.cfg


Note: these are not HOW TO steps for setting up Klipper, only working files from my config and some reference info.

printer.cfg
I am making this file available as I am setting up my first Klipper printer, as finding a good working printer.cfg file is proving not that easy.

klipper.bin 
This file is for the SD card to flash to the printer (turn printer off, unplug native display, unplug usb cable, insert SD card, turn on, wait a few seconds, connect usb cable from your pi running Klipper Mainsail OS)

Isues:
STILL GETTING OUT OF RANGE ERROR AT END OF PRINT:
Move out of range: 0.000 235.000 20.120 [542.884]
RESOLVED: In Cura (slicer), Settings, Printer, Manage, Machine Settings, update X and Y from default 235 to 220 (actual printable area)

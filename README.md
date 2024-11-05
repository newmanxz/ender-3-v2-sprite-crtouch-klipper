# ender-3-v2-sprite-crtouch-klipper

<!-- push test1 -->
From:

https://github.com/Klipper3d/klipper

https://github.com/Klipper3d/klipper/blob/master/config/printer-creality-ender3-2018.cfg




NOTE : These are not HOW TO steps for setting up Klipper, only working files from my config, and some reference info.

printer.cfg : I am making this file available as I am setting up my first Klipper printer, because finding a good working printer.cfg file is proving rather dificult.

klipper.bin :  I compiled this bin file for my printer and it works for me; it may work for you. Download and copy the klipper.bin file to your micro SD card, turn printer off, unplug native display (it stays unplugged permanently), unplug usb cable, insert SD card, turn printer on, wait a few seconds for the printer to flash, connect USB cable from your PI running Klipper Mainsail OS.

ISSUE Move out of range 0.000 235.000 (solved): In Cura (slicer), Settings, Printer, Manage, Machine Settings, update X and Y from default 235 to 220 (actual printable area).

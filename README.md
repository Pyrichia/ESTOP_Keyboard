This is a very simple json file for use with QMK toolbox; all it does is make a macro for hitting CTRL_Z when pin9 is bridged to ground.
In this case, it's done with an ESTOP button.

If you wish to have this button do anything else, just modify the JSON file and rebuild with QMK Toolbox to make a new .hex file.
Plug the Pro Micro into the computer and get its COM port, select this in QMK Toolbox. To flash, you must bridge RST and GND twice in quick
succession to put it into bootloader mode for flashing. Turn on Auto-Flash in QMK Toolbox to auto-upload as soon as it shows up.
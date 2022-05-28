# Jankbot
### Firmware flashing options
* Board: STM32F429
* Bootloader: 32Kb
* Run make and copy generated file `out/klipper.bin` to sd card, named `firmware.bin`
* Insert SD card to SKR 2 and reboot

### Printer info
* Board: BIGTREETECH SKR 2 with STM32F249 controller
* Display: BTT Pi TFT50 V2.0
* Drivers: 5x TMC2209
* Z motors driven seperately
* XY homing: sensorless
* Z homing: BLTouch Clone

# Links
* Config originally built off of https://github.com/Klipper3d/klipper/blob/master/config/generic-bigtreetech-skr-2.cfg
* Klipper config reference: https://www.klipper3d.org/Config_Reference.html
* Jinja2 template reference: https://jinja.palletsprojects.com/en/2.10.x/templates/
* BTT SKR 2 Manual: https://github.com/bigtreetech/SKR-2/blob/master/Hardware/BIGTREETECH%20SKR%202%20user%20manual.pdf
* Klipper command templates (gcode macros): https://www.klipper3d.org/Command_Templates.html
* Klipper status reference (available variables): https://www.klipper3d.org/Status_Reference.html
* Klipper extended
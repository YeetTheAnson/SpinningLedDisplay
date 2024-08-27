# SpinningLedDisplay
Line of leds spinning in a circle to make a display

![SpinningLedDisplay](https://github.com/YeetTheAnson/SpinningLedDisplay/raw/main/1.png)
![SpinningLedDisplay](https://github.com/YeetTheAnson/SpinningLedDisplay/raw/main/2.png)

## Overview

**SpinningLedDisplay** is an array of led, with a hall effect sensor to sync the led while spinning to create a circular display using the principle of persistent vision

The gerber files can be found [here](https://github.com/YeetTheAnson/SpinningLedDisplay/tree/main/GerberFile/)
The 3d view of the pcb can be found [here](https://www.flux.ai/yeettheanson/spinningleddisplay?editor=pcb_3d)


## Datasheets and References

The information i referred to while building the PCB is here
- **[ESP8266EX](https://www.espressif.com/sites/default/files/documentation/0a-esp8266ex_datasheet_en.pdf)**
- **[ACS712ELCTR-20A-T Hall Effect Sensor](https://www.sparkfun.com/datasheets/BreakoutBoards/0712.pdf)** 
- **[AMS1117-3.3 LDO](https://mm.digikey.com/Volume0/opasdata/d220001/medias/docus/5011/AMS1117.pdf)**
- **[74HC595D Shift Register](https://www.mouser.com/datasheet/2/408/toshiba_74HC595D(X34TTD-410-02)_E_20160209-1209527.pdf)**


## Features

- Hall effect sensor to sync rotation speed with led
- ESP8266 for wireless OTA flashing and LED control
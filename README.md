# Tinyduino

## Overview
The Arduino Nano is one of my favorite microcontrollers, so I decided to make my own small microcontroller; the Tinyduino!

The Tinyduine is about 20% smaller than a regular Arduino Nano, and all the components are on the top side, so it can be flush-soldered to a PCB or perfboard for more permanent projects. It can be powered by 5 volts directly, or 7 to 12 volts through the VIN pin.

Like a regular Arduino, you can just plug the board into your computer to upload code. The AtTiny 806 microcontroller is 100% compatible with Arduino code thanks to the awesome MegaTinyCore, and it offers a ton of additional benefits over a traditional Arduino:

* 18 GPIO, 12 of which are analog inputs, and 6 of which are PWM

* Onboard LED for debugging on Pin #0

* 25% faster clock speeds, up to 20MHz.

* Pin remapping; Ever wish the i2C or SPI pins were in a different spot? Well now they can be! The 806 supports repositioning of the SPI, i2C, and UART pins.

* Multiple Internal References; The 806 has multiple different voltages that can be referenced as internal analog pins.

* Hardware Comparator; The 806 includes an analog comparator, that can be used to fire an interrupt, wake the microcontroller, or set an I/O to be high or low.

* Fast I/O; MegaTinyCore supports digitalWriteFast and digitalReadFast, which greatly increase the speed of IO for time-sensitive applications.

* All pins can be used as an interrupt in any form, or to wake the microcontroller.

* Programmable ADC resolution and speed

* Software-defined clock speeds, down to 1MHz for ultra low-power operation.

* In the future I am also hoping to switch to a 1-series AtTiny instead of a 0-series (had to settle due to silicon shortages), this'll allow;

* Digital to Analog Conversion; output a programmable voltage on pins.

* More RAM, program memory, and EEPROM

* Multiple timers running concurrently

* Overclocking up to 30MHz

The best part is that the Tinyduino costs significantly less than a genuine Arduino, and is nearly as inexpensive as a Chinese clone Nano.

## Photos & Media
Photos of the project can be found on my portfolio, [here](https://www.jim-heaney.com/tinyduino.html).

## Current Release
There is no stable release of the Tinyduino, the files linked here should work in theory, but have not been extensively tested.

## Current State
The Tinyduino is still an active project, but I have put it on hold due to the ongoing chip shortage.

## Featured In...

[Microchip Makes](https://www.instagram.com/p/CPYs_vFn-YU/)

## Support Me
You can also buy me a coffee [here](https://www.buymeacoffee.com/jimheaney)!

## License
This project is licensed under the Creative Commons 4.0 Attribution-NonCommercial-ShareAlike. For more information, click [here](https://creativecommons.org/licenses/by-nc-sa/4.0/).

If you want to use this project under a different license, please contact me. 

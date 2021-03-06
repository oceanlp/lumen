# *Lumen* Subsea Lights

The *Lumen* Subsea Light is an underwater, pressure-rated LED light capable of outputting over 1500 lumens. 

The schematic and board layout are designed in EagleCAD.

# *Lumen* Subsea Light Hardware

## Features 

* 1500+ lm output
* Onboard microcontroller (ATTiny45) for programmable behavior
* Multiple signal input types:
	* Standard servo PWM input signal (1100-1900 microseconds)
	* Direct duty cycle control (with solder jumper)
	* On/off control with no signal needed by connecting signal wire to power
* Daisy-chainable to allow multiple lights from a single cable
* Thermistor temperature feedback and overheating protection
* 6-48V input range
* 0-2.5A LED output

## Software

The software running on the onboard microcontroller is available in the *Lumen-Arduino* directory and can be installed with the Arduino IDE and an AVR-ISP programmer.

## License

The Lumen Subsea Light Hardware Design is released under the MIT License.

## Revision History

0.0 - Under development

0.1 - First production version

0.11 - First production version w/ software
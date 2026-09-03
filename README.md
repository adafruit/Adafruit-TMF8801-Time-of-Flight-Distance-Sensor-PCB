## Adafruit TMF8801 Time of Flight Distance Sensor - 20mm to 2.5m - STEMMA QT / Qwiic PCB

<a href="http://www.adafruit.com/products/6522"><img src="assets/6522.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit TMF8801 Time of Flight Distance Sensor - 20mm to 2.5m - STEMMA QT / Qwiic. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6522

### Description

The <b>Adafruit TMF8801 Time of Flight Sensor</b> is a great <i>Time of Flight</i> distance sensor from ams Osram in the TMF series of chips. The TMF8801 in particular can do 20mm to 2.5 meters at 33 Hz update rate.

The sensor contains a very tiny invisible laser source and a matching sensor. The TMF8801 can detect the "time of flight", or how long the light has taken to bounce back to the sensor. Since it uses a very narrow light source, it is good for determining distance of only the surface directly in front of it. Unlike sonars that bounce ultrasonic waves, the 'cone' of sensing is very narrow. Unlike IR distance sensors that try to measure the amount of light bounced, the TMF is much more precise and doesn't have linearity problems or 'double imaging' where you can't tell if an object is very far or very close.

One nice thing about this sensor is that while it does require a firmware 'patch' on boot and the SRAM usage is also much lighter, so it fits easily in small memory boards like the ATmega328. You can use it on many 8-bit microcontroller devices.

The sensor is small and easy to use in any robotics or interactive project. Since it needs 3.3V power and logic we put the little fellow on a breakout board with a regulator and level shifting. You can use it with any 3-5V power or logic microcontroller with no worries. Works great with the <b>3.3V logic level of a Feather, or the 5V level of a ATmega</b>, this breakout is ready to work with most common microcontrollers or SBCs. and since it speaks I2C, you can easily connect it up with two data wires plus power and ground. 

As if that weren't enough, we've also added [SparkFun qwiic](https://www.sparkfun.com/qwiic) compatible [STEMMA QT](https://learn.adafruit.com/introducing-adafruit-stemma-qt) connectors for the I2C bus so you <b>don't even need to solder</b>. Just wire up to your favorite micro with a plug-and-play cable to get ToF data ASAP. For a no-solder experience, just wire up to your favorite micro using a [STEMMA QT adapter cable](https://www.adafruit.com/?q=stemma%20qt%20cable). The Stemma QT connectors also mean the TMF8801 can be used with our [various associated accessories](https://www.adafruit.com/?q=JST%20SH%204). [QT Cable is not included, but we have a variety in the shop](https://www.adafruit.com/?q=stemma+qt+cable&sort=BestMatch).

Communicating to the sensor is done over I2C, [check out our Arduino and CircuitPython/Python code](https://github.com/adafruit?q=TMF8801&type=all&language=&sort=) to get started fast and read data over I2C in a jiffy.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.

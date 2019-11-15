## Adafruit PA1010D Mini GPS Module PCB

<a href="http://www.adafruit.com/products/4415"><img src="assets/4415.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit PA1010D Mini GPS Module. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4415

### Description

This miniature GPS breakout is only 1" x 1" (~ 25mm x 25mm) but houses a complete GPS/GNSS solution with both I2C and UART interfaces. There's even an antenna on top so it's plug and play!

* Support for GPS, GLONASS, GALILEO, QZSS
* -165 dBm sensitivity, up to 10 Hz updates
* Up to 210 PRN channels with 99 search channels and 33 simultaneous tracking channels
* 5V friendly design and only 30mA current draw
* Breadboard-able, with 4 mounting holes
* UART and I2C interfaces, pick whichever you like most!
* RTC battery-compatible
* PPS output on fix ±20ns jitter
* Internal patch antenna
* Low-power and standby mode with WAKE pin

The breakout is built around the MTK3333 chipset, a reliable, high-quality GPS module that can handle up to 33 simultaneous tracking channels, has an excellent high-sensitivity receiver (-165 dBm tracking!), and a built in antenna. It can do up to 10 location updates a second for high speed, high sensitivity logging or tracking. Power usage is incredibly low, only 30 mA during navigation.

Best of all, we added all the extra goodies you could ever want: a ultra-low dropout 3.3V regulator so you can power it with 3.3-5VDC in, 5V level safe inputs on UART and I2C, a footprint for optional CR1220 coin cell to keep the RTC running and allow warm starts, a green power LED and a tiny red PPS LED. The LED blinks at about 1Hz when a fix is found and is off when no fix.

Unlike our Ultimate GPS modules, this module does not have the ability to connect an external antenna, it's designed to be as small as possible for compact projects.

As with all Adafruit breakouts, we've done the work to make this GPS module super easy to use. We've put it on a breakout board with the required support circuitry and connectors to make it easy to work with, and is now a trend we've added SparkFun Qwiic compatible STEMMA QT JST SH connectors that allow you to get going without needing to solder. Just use a STEMMA QT adapter cable, plug it into your favorite micro or Blinka supported SBC and you're ready to rock!

Comes with one fully assembled and tested module, a piece of header you can solder to it for bread-boarding, and a CR1220 coin cell holder. A CR1220 coin cell is not included, but we have them in the shop if you'd like to use the GPS's RTC

We have a nice fancy library for GPS usage for both Arduino and Python usage. A full tutorial is also available, which has tons of information about the module, how to use the data logger, example code for both CircuitPython & Arduino, and more

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.

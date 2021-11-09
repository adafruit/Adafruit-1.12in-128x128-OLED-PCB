## Adafruit Monochrome 1.12in 128x128 OLED Graphic Display PCB

<a href="http://www.adafruit.com/products/5297"><img src="assets/5297.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Monochrome 1.12in 128x128 OLED Graphic Display. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5297

### Description

This OLED goes out to all the fans who want more pixels in a smaller size! Normally our 128x64 OLEDs are the biggest ones we've stocked that can use I2C. This one is a whopping 128x128 pixels in crisp monochrome.

This display is a petite 1.12" diagonal, but very readable due to the high contrast of an OLED display. This display is made of 128x128 individual white OLED pixels, each one is turned on or off by the controller chip. Because the display makes its own light, no backlight is required. This reduces the power required to run the OLED and is why the display has such high contrast; we really like these miniature displays for their crispness!

The driver chip, SSD1107 can communicate in two ways: I2C or SPI. The OLED itself requires a 3.3V and 12V power supply and 3.3V logic levels for communication. We include a 3.3V regulator and 12V boost converter, and all pins are fully level shifted so you can use with 3V or 5V devices!

If you are using I2C, we've included SparkFun qwiic compatible STEMMA QT connectors for the I2C bus so you don't even need to solder! Plug and play with any board that has a Qwiic or STEMMA QT connector for effortless prototyping and development. QT Cable is not included, but we have a variety in the shop.

This display, being 128x128 pixels, requires 128 * 128 = 2KB of SRAM just to buffer the display. So you can't use it with a small chip such as the Arduino UNO (ATmega328 or 32u4). Pick a microcontroller or microcomputer with 16KB+ RAM - a SAMD21, SAMD51, ESP, nRF52, Teensy, etc will do an excellent job. As long as you have I2C or SPI interface available, you're good to go - SPI will be much faster but I2C requires fewer pins.

We have both Arduino and CircuitPython support for this display chipset (SH1107).

Please note that OLED displays are made of hundreds of...OLEDs! That means each pixel is a little organic LED, and if it's kept on for over 1000 hours it'll start to dim. If you want to keep the display uniformly bright, please turn off the display (set the pixels off) when it isn't needed to keep them from dimming.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.

## Adafruit Feather RP2040 RFM PCB

<a href="http://www.adafruit.com/products/5712"><img src="assets/5712.jpg?raw=true" width="500px"><br/>
<a href="http://www.adafruit.com/products/5714"><img src="assets/5714.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Feather RP2040 RFM69 and RFM9x. The board files are identical for both
types of radio modules!

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5712

### Description

This is the Adafruit Feather RP2040 RFM. We call these RadioFruits, our take on a microcontroller with packet radio transceiver with built-in USB and battery charging. It's an Adafruit Feather RP2040 with a radio module cooked in! Great for making wireless networks that are more flexible than Bluetooth LE and without the high power requirements of WiFi.

Feather is the development board specification from Adafruit, and like its namesake, it is thin, light, and lets you fly! We designed Feather to be a new standard for portable microcontroller cores. We have other boards in the Feather family, check'em out here.

It's kinda like we took our RP2040 Feather and an RFM breakout board and glued them together. You get all the pins for use on the Feather, the Lipoly battery support, USB C power / data, onboard NeoPixel, 8MB of FLASH for storing code and files, and then with the 8 unused pins, we wired up all the DIO pins on the RFM module. There's even room left over for a STEMMA QT connector an a uFL connector for connecting larger antennas.

At the Feather's heart is an RP2040 chip, clocked at 133 MHz and at 3.3V logic, the same one used in the Raspberry Pi Pico. This chip has a whopping 8MB of onboard QSPI FLASH and 264K of RAM! This makes it great for making wireless sensor nodes that can send to each other without a lot of software configuration.

To make it easy to use for portable projects, we added a connector for any of our 3.7V Lithium polymer batteries and built-in battery charging. You don't need a battery, it will run just fine straight from the USB Type C connector. But, if you do have a battery, you can take it on the go, then plug in the USB to recharge. The Feather will automatically switch over to USB power when its available.

Here're some handy specs! You get:
* Measures approximately 2.0" x 0.9" x 0.28" (50.8mm x 22.8mm x 7mm) without headers soldered in
* Light as a (large?) feather - approximately 6 grams
* RP2040 32-bit Cortex M0+ dual core running at ~133 MHz @ 3.3V logic and power
* 264 KB RAM
* 8 MB SPI FLASH chip for storing files and CircuitPython/MicroPython code storage. No EEPROM
* Tons of GPIO! 21 x GPIO pins with following capabilities:
* Four 12-bit ADCs (one more than Pico)
* Two I2C, Two SPI, and two UART peripherals, we label one for the 'main' interface in standard Feather locations
* 16 x PWM outputs - for servos, LEDs, etc
* Built-in 200mA+ lipoly charger with charging status indicator LED
* Pin #13 red LED for general purpose blinking
* RGB NeoPixel for full-color indication.
* On-board STEMMA QT connector that lets you quickly connect any Qwiic, STEMMA QT or Grove I2C devices with no soldering!
* Both Reset button and Bootloader select button for quick restarts (no unplugging-replugging to relaunch code)
* USB Type C connector lets you access built-in ROM USB bootloader and serial port debugging
* 3.3V Power/enable pin
* 4 mounting holes
* 12 MHz crystal for perfect timing.
* 3.3V regulator with 500mA peak current output

We squished all the parts on our Feather RP2040 over towards the USB port to make some room on the end. This Feather RFM uses the extra space left over to add an RFM radio module. These radios are not good for transmitting audio or video, but they do work quite well for small data packet transmission when you need more range than 2.4 GHz (BT, BLE, WiFi, ZigBee).

Radio module specifications:

* SX1231 or SX127x LoRa® based module with SPI interface
* +13 to +20 dBm up to 100 mW Power Output Capability (power output selectable in software)
* 50mA (+13 dBm) to 150mA (+20dBm) current draw for transmissions, ~30mA during active radio listening.
* Range of approx. 500 meters to 2Km, depending on which RFM module, as well as obstructions, frequency, antenna and power output
* Create multipoint networks with individual node addresses
* Encrypted packet engine with AES-128
* Packet/LoRa radio with ready-to-go Arduino & CircuitPython libraries
* Uses the license-free ISM bands (ITU "Europe" @ 433MHz and ITU "Americas" @ 900MHz)
* Simple wire antenna can be soldered into a solder pad, there's also a uFL connector that can be used with uFL-to-SMA adapters for attaching bigger antennas.

* Comes fully assembled and tested, we also toss in some headers so you can solder it in and plug into a solderless breadboard. You will need to cut and solder on a small piece of wire (any solid or stranded core is fine) in order to create your antenna. or use a uFL connector and an appropriate SMA antenna. Lipoly battery and USB cable are not included, but we do have lots of options in the shop if you'd like!

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.

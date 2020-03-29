# Croduino NOVA Eagle Files
[![e-radionica.com logo](https://e-radionica.com/productdata/static-pics/email-logo.png)](https://e-radionica.com)
![Croduino NOVA image](https://e-radionica.com/media/catalog/product/d/s/dsc_4844.jpg)
Buy [Croduino NOVA(100026)](https://e-radionica.com/en/croduino-nova.html) here

## Description and details
Croduino NOVA is microcontroller board capable of connecting to WiFi Internet network, made in Croatia(EU). It is based on very popular ESP8266 which is struggle to use standalone. With NOVA, just plug the board into USB port and start programming your next Internet-connected project(IoT)! Besides that, the board fits perfectly into a breadboard so prototyping is even more simple. Connecting the physical world to internet was never easier.

The braing of NOVA is ESP8266 produced by Espressif. It comes with complete WiFi(client and server side) and integrated TCP/IP stack which supports DNS. The most important thing - it is programmable from Arduino, there is even no need to manually reset the board due to auto-reset circuit onboard. It works at 80MHz frequency, has 1MB of flash for your code(of which 0.8MB available to you) and 82kB of RAM memory(of which 49kB available to you). NOVA also supports I2C, SPI and serial communication, there is 9 GPIO for you of which all support PWM and 1 analog input. Additionally, there is onboard: CP2102 USB to UART bridge (used for USB communication), 3.3V voltage regulator, 4 LEDs, it has FCC and CE certificate etc. In detail:

- ESP8266 in ESP-12 package
- 80MHz, 1MB flash, 82kB RAM
- programmable from Arduina!
- 9 GPIO pins of which all support PWM
- 1 analog input(ADC), max. voltage 1V i 5V
- I2C, SPI, serial communication
- CP2102 USB to UART bridge with micro USB connector
- 3.3V voltage regulator
- LEDs: power, tx, rx, GPIO13
- automatical hardware reset before upload of code
- two pushbuttons: reset i GPIO0
- comes with micro USB cable
- FCC i CE certificates for ESP-12

ESP8266 on-board is loaded with default bootloader.

## Repository content
This repo contains Cadsoft Eagle .sch and .brd files for Croduino NOVA board. It also contains schematic in .pdf created from .sch Eagle file. 
Files have been arranged into folders for navigating between different versions of board. 
Tip: layer 200 shows top silkscreen and layer 208 is the bottom silkscreen. tParts and bParts layers are not used.

## Docs
- [Croduino NOVA product page](https://e-radionica.com/en/croduino-nova.html)

## Board versions
- v1.0 - inital published version 
- v1.1 - there was error near GPIO1 pushbutton in which GPIO0 was always directly connected to gnd. Fixed now. Silkscreen text is also a bit bigger and more readable.
- v1.2 - slight redesign, board longer 5mm and wider 2.54mm, added battery charger, changed LDO, parts rearranged. 

## License info
This product is [Open Source Hardware](https://en.wikipedia.org/wiki/Open-source_hardware), yay! Feel free to use it for any purpose you wish, but if you are ever in [Osijek, Croatia](https://goo.gl/maps/tEC2jWnBXJQpk9RJ7), you owe us a beer.

For any tech questions, please write on our [forum](http://forum.e-radionica.com/en/). If you find an Issue, please open one at GitHub. If you can improve our product, fork us.

e-radionica.com Team.

connections:
TFT -> Arduino Mega 2560 pin | ATMEGA2560 pin
LCD_RD -> A0 | PF0
LCD_WR -> A1 | PF1
LCD_RS -> A2 | PF2
LCD_CS -> A3 | PF3
LCD_RST -> A4 | PF4

LCD_D2 -> 2 | PE4
LCD_D3 -> 3 | PE5
LCD_D4 -> 4 | PG5
LCD_D5 -> 5 | PE3
LCD_D6 -> 6 | PH3
LCD_D7 -> 7 | PH4

LCD_D0 -> 8 | PH5
LCD_D1 -> 9 | PH6

all the rest:
This is a library for the Adafruit 2.8" TFT display.
This library works with the Adafruit 2.8" TFT Breakout w/SD card
  ----> http://www.adafruit.com/products/335
as well as Adafruit TFT Touch Shield
  ----> http://www.adafruit.com/products/376
 
Check out the links above for our tutorials and wiring diagrams.
These displays use 8-bit parallel to communicate, 12 or 13 pins are required
to interface (RST is optional).
Adafruit invests time and resources providing this open source code,
please support Adafruit and open-source hardware by purchasing
products from Adafruit!

Written by Limor Fried/Ladyada for Adafruit Industries.
MIT license, all text above must be included in any redistribution

To download. click the DOWNLOADS button in the top right corner, rename the uncompressed folder Adafruit_TFTLCD. Check that the Adafruit_TFTLCD folder contains Adafruit_TFTLCD.cpp and Adafruit_TFTLCD.

Place the Adafruit_TFT library folder your <arduinosketchfolder>/libraries/ folder. You may need to create the libraries subfolder if its your first library. Restart the IDE

Also requires the Adafruit_GFX library for Arduino. https://github.com/adafruit/Adafruit-GFX-Library

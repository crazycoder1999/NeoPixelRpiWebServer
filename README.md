# NeoPixelRpiWebServer
This project helps anyone to control LEDS on a NeoPixel Led Strip, thanks to 2 simple  HTTP Get:
- http://ip:8083/switchAllOff? will switch off all the leds
- http://ip:8083/changeLed?ledId=[0-7]&red=[0-255]&green=[0-255]&blue=[0-255]&brightness=[0-100] will change the ledId selected with the color (red,green,blue) and the brightness passed.

# Schematics
Configuration tested with a Raspberry Pi Zero W
![Alt text](rpi_neopixel_stripled.png?raw=true "Schematic")


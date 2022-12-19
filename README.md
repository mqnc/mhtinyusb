# MHTinyUSB
Copy of the Digispark libraries, added configurations to work with the MH-ET LIVE Tiny88 board

Note that I have so far only tried the DigiCDC library, but the others should just work without trying as things always do.

## Installation
Download zip files of the libraries you need

In Arduino IDE: Sketch -> Include Library -> Add .ZIP Library

## Usage
See examples on how to use

## Sources
Original Digispark Libraries:

https://github.com/digistump/DigistumpArduino/tree/master/digistump-avr/libraries

The only changes I made are in usbconfig.h; I added port and interrupt settings for the ATtiny88 which I got from here:

https://github.com/micronucleus/micronucleus/blob/master/firmware/configuration/t88_default/bootloaderconfig.h

## Enjoy Wishing
Enjoy!

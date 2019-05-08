# Pos-Printer-Library

This is an Arduino library for a POS(point of sale) Printer.
This library is testet on a samsung SRP-350G printer.
These printers use TTL serial to communicate, 2 pins are required.
But can have rs-232 or other cards in the back, that convert othersignals to ttl, so you might need a soldering iron to add 2-3 wires. 

## ARDUINO LIBRARY LOCATION

On your Mac:: In (home directory)/Documents/Arduino/Libraries
On your PC:: My Documents\Arduino\libraries
On your Linux box: (home directory)/sketchbook/libraries

## About library

Written by Anders Vesterga
ard, with contributions from the open source community.  Originally based on adafruit thermal printer library https://github.com/adafruit/Adafruit-Thermal-Printer-Library
MIT license, all text above must be included in any redistribution.

If you don't need to print danish characters like "æøåÆØÅ" then you should comment the line in POS_printer.cpp that defines DENMARK

I have a danish wiki page for the project on the local hackerspace's wiki http://wiki.hal9k.dk/projects/posprinter
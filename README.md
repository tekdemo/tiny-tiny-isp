tiny-tiny-isp
=============
A very small ISP programmer for AVR chips.

Based heavily off of the VUSBTiny-AVR-SPI-Programmer](http://www.instructables.com/id/VUSBTiny-AVR-SPI-Programmer/), with some additional features. 


Features
========

- Level shifting options for 3.3V, 5V programming

- Option for high-voltage reset

- Very small footprint

- Low cost design

- Ability to use pogo pins for quick programming, or use headers for prototyping

*Wishlist*

- Integrate USB-COM support to allow target to pass messages to host via SPI
 

Board Changelog
========

*V2*

- Fix current limiting resistors being on the wrong side of the diode

- Fix missing pull-up resistors on target side of level-shifting mosfets

- Add a place to connect 12V for high-voltage reset 

- Improved bottom graphic

- Improved pad layout for pogo pins


*V1*

- Initial Design board layout



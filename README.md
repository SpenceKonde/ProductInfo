# ProductInfo
This repositort is the official source for information on products sold by [Azzy's Electronics](https://www.tindie.com/stores/drazzy/), my Tindie store. All official information will be contained here; the old official website information pages will be shut down, as it has been found that, in practice, maintenance of the site proved too labor intensive, and consequently, it was always out of date. Currently this is in an early stage of construction. 

### Issues are enabled here 
**Please do not hesitate to open one** if you find inaccurate information here, or if a product is not adequately described here. Of course you can also email me (spencekonde@gmail.com) or use the Tindie messaging system. This is preferred for documentation or product page problems. Issues are publically viewable - to protect your privacy, please use email or Tindie message for problems with an order (Tindie message has the benefit of being viewable by Tindie support staff in case you are not satisfied with my response and feel a need to escalate; I strive for customer satisfaction, and this has rarely happened in the history of my store)

## Product Catalog

### AVR breakout and development boards
We sell a breakout and development board for nearly every part supported by the Arduino cores that I maintain. While the cores - of course - can be used without one of these official breakout boards, in many cases there is no readily available general purpose breakout/development board on the market. These provide a route by which hobbyists can take advantage of the unique features of these parts, and users who plan to design their own hardware (a common situation) can perform initial prototyping without having to design and build a board just to connect to the part and perform initial development. 

#### AVR DA-series

**These boards are documented here** 
[Modern AVR Breakout Board Documentation](https://docs.google.com/document/d/1IWnycuZnM8XzgPuqVQK-ig7smtBS3EVSk9u_J4qsq-I)
Most documentation is contained only in that document, not in here (issues can still be reported through this repo's issues function)

#### tinyAVR 0/1-series 
The "modern" tinyAVR (ATtiny) devices released by ~Atmel~ Microchip since 2016 are supported by [megaTinyCore](https://github.com/SpenceKonde/megaTinyCore). These parts feature memory mapped flash (ie, you don't need to use PROGMEM to put constants into flash, nor the F() macro when printing strings). They also have the same "modern" style peripherals like the megaAVR 0-series (ex, the ATmega4809 used on Nano Every and WiFi Rev. 2), which are typically superior to the "classic" peripherals, and on the 1-series parts, a few new ones (like the Type D async timer). They represent the future of the tinyAVR line - Microchip has indicated that all future parts will follow in the footsteps of these, not the "classic" tinyAVR parts; accordingly we recommend using them when possible, rather than the older parts.

These have 8, 14, 20, or 24 pins. All have 2 power/ground pins, one UPDI pin which can be reconfigured as Reset or I/O, and the rest are normal I/O pins). The top-end versions of these are the ATtiny412/402, ATtiny1614/1604, ATtiny3216/1606, and ATtiny3217/1607. The 0-series parts are strictly inferior to the 1-series parts, and their only advantage is a slightly lower cost. Except for development of cost-sensitive products, the 1-series parts are a better choice. 

**These boards are documented here** 
[Modern AVR Breakout Board Documentation](https://docs.google.com/document/d/1IWnycuZnM8XzgPuqVQK-ig7smtBS3EVSk9u_J4qsq-I)
Most documentation is contained only in that document, not in here (issues can still be reported through this repo's issues function)

#### "Classic" tinyAVR
All tinyAVR (ATtiny) parts released prior to 2016 use what I refer to as the "classic" peripherals, and have a high degree of similarity with the megaAVR devices from that era, including the incredibly popular ATmega328. These parts are supported by ATTinyCore, and we sell breakout boards in our usual style for all parts that are not available in a DIP package, and a few that are. 

Unlike the "modern" parts, even where parts have the same number of pins, they are typically not pin compatible outside of a given family. Like classic megaAVR parts, the family is identified by the portion of the part number after the flash size.

#### megaAVR 0-series
The "modern" megaAVR (ATmega) parts were released in 2016, and are supported on Arduino by MCUDude's excellent MegaCoreX core. Because these are pin compatibile with the DA-series parts, we also offer them mounted on our breakout board. 

These devices have 48 or 32 pins (with 40 and 26 I/O pins respectively, plus reset (which can be used as an I/O pin based on fuse configuration), UPDI, and power/ground pins. The top-end parts are the 4809, 4809; they are also available with 8, 16, 32, and 48k of flash.

**These boards are documented here** 
[Modern AVR Breakout Board Documentation](https://docs.google.com/document/d/1IWnycuZnM8XzgPuqVQK-ig7smtBS3EVSk9u_J4qsq-I)
Most documentation is contained only in that document, not in here (issues can still be reported through this repo's issues function)

## Prototyping Board

## MOSFETs

## Special Orders
We can do special orders (such as a different part or parts mounted on one of our breakout boards) as well as custom design work. Email SpenceKonde@gmail.com for more information.

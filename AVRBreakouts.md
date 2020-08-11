# AVR breakout and development boards
We sell a breakout and development board for nearly every part supported by the Arduino cores that I maintain. While the cores - of course - can be used without one of these official breakout boards, in many cases there is no readily available general purpose breakout/development board on the market. These provide a route by which hobbyists can take advantage of the unique features of these parts, and users who plan to design their own hardware (a common situation) can perform initial prototyping without having to design and build a board just to connect to the part and perform initial development. 

## AVR DA-series
The new AVR DA-series, released by Microchip in 2020, brings the 8-bit AVR product line to a whole new level, with significant enhancements to almost every system. Highlights include a 12-bit ADC (10-bit mode available), 10-bit DAC, internal oscillator up to 24 MHz, 1.8-5.5V operation (including 24 MHz at 1.8v, not the 4-5@1.8V of previous AVRs), on-chip PLL that can clock timer D at up to 48 MHz, with 128k of flash and 16k of RAM in the top-end version. In short, the part that every AVR programmer has always wished existed. 

Well, now they do. 

Arduino support will be available using my upcoming DxCore from first week of August 2020, with simultaneous launch of our line of breakout boards for the 32, 48, and 64 pin devices (we do not produce a breakout board for the 28-pin version.
**These boards are documented here** 
[Modern AVR Breakout Board Documentation](https://docs.google.com/document/d/1IWnycuZnM8XzgPuqVQK-ig7smtBS3EVSk9u_J4qsq-I)
That document contains the most complete and up-to-date information about these breakout boards.

## tinyAVR 0/1-series 
The "modern" tinyAVR (ATtiny) devices released by ~Atmel~ Microchip since 2016 with better peripherals and (except in 8-pin parts) more memory than the "classic" ATtiny parts.  Trey are supported on Arduino by my [megaTinyCore](https://github.com/SpenceKonde/megaTinyCore) - see that link for more information about their capabilities in an Arduino context. 

All pins are broken out into two rows of header, and there are 3 or 4 pins each connected to power and ground, a 6-pin FTDI style header (optionally available with AutoReset wired up), a regulator (at 5v or 3.3v, optionally replaced with jumper for low power applications), PTC fuse protected Vin header and LED. 

**These boards exhaustively documented here** 
[Modern AVR Breakout Board Documentation](https://docs.google.com/document/d/1IWnycuZnM8XzgPuqVQK-ig7smtBS3EVSk9u_J4qsq-I)
That document contains the most complete and up-to-date information about these breakout boards.

### [24-pin ATtiny3217/1607 Assembled  ](https://www.tindie.com/products/17523/)
`https://www.tindie.com/products/17523/`
### [24-pin ATtiny3217/1607/similar Bare Board  ](https://www.tindie.com/products/17613/)
`https://www.tindie.com/products/17613/`

### [20-pin ATtiny3216/1606 Assembled](https://www.tindie.com/products/17597/)
`https://www.tindie.com/products/17597/`
### [20-pin ATtiny3216/1606/similar Bare Board](https://www.tindie.com/products/17614/)
`https://www.tindie.com/products/17614/`

### [14-pin ATtiny1614/1604 Assembled](https://www.tindie.com/products/17598/)
`https://www.tindie.com/products/17598/`
### [14-pin ATtiny1614/1604/similar Bare Board](https://www.tindie.com/products/17748/)
`https://www.tindie.com/products/17748/`

### [8-pin ATtiny412/402 Assembled](https://www.tindie.com/products/17685/)
`https://www.tindie.com/products/17685/`
### [8-pin ATtiny412/402/similar Bare Board](https://www.tindie.com/products/17749/)
`https://www.tindie.com/products/17749/`

## "Classic" tinyAVR
All tinyAVR (ATtiny) parts released prior to 2016 use what I refer to as the "classic" peripherals, and have a high degree of similarity with the megaAVR devices from that era, including the incredibly popular ATmega328. These parts are supported by ATTinyCore, and we sell breakout boards in our usual style for all parts that are not available in a DIP package, and a few that are. 

Unlike the "modern" parts, even where parts have the same number of pins, they are typically not pin compatible outside of a given family. Like classic megaAVR parts, the family is identified by the portion of the part number after the flash size.

## megaAVR 0-series
The "modern" megaAVR (ATmega) parts were released in 2016, and are supported on Arduino by MCUDude's excellent [MegaCoreX](https://github.com/MCUdude/MegaCoreX) core. Because these are pin compatibile with the DA-series parts, we also offer them mounted on the same breakout board as we made for the 32 and 48 pin DA-series parts.

These devices have 48 or 32 pins (with 40 and 26 I/O pins respectively, plus reset (which can be used as an I/O pin based on fuse configuration), UPDI, and power/ground pins. The top-end parts are the 4809, 4809; they are also available with 8, 16, 32, and 48k of flash.



**These boards are documented here** 
[Modern AVR Breakout Board Documentation](https://docs.google.com/document/d/1IWnycuZnM8XzgPuqVQK-ig7smtBS3EVSk9u_J4qsq-I)
Most documentation is contained only in that document, not in here (issues can still be reported through this repo's issues function)

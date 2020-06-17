# FireBox

[Kickstarter campaign](www.wasatchscalemodels.com) for FireBox

## What is FireBox?

Most simply - FireBox is a custom hardware solution for DCC++ EX that is small, cheap, powerful, and extensible.

Boasting a 5 amp capable main track, FireBox packs a powerful processor that is faster and more capable than existing DCC++ systems. The board is fully compatible with JMRI software, and supports addressing up to 255 locomotives simultaneously and managing over a thousand turnouts.

FireBox is open source - both hardware and software. That means that you can tinker with it and build your own expansion boards, or make your own!
 
## Why FireBox?
DCC++ EX is a great system, but the most basic hardware setup (an Arduino with an Arduino Motor Shield) can only supply 2A per track, doesn't come with WiFi, can't support RailCom, and requires assembly. 

FireBox leverages recent improvements in DCC++ EX software and combines them with brand-new hardware. As a result, it is capable of driving more locomotive addresses and sourcing more current - up to 5 amps! That's 8-10 locomotives in HO scale and 16-20 in N scale. FireBox is ready to run out of the box, and includes WiFi. Firebox also supports RailCom out of the box!

## What's RailCom?
RailCom is an NMRA standard developed by Lenz Elektronik GmbH to allow locomotives to talk back to the command station when they're out on the layout - you can get speed reports, see how much fuel is left in the locomotive, and even read/write CVs (Configuration Variables) on the main track! Not all decoders support RailCom, but all DCC-equipped locomotives can run on a RailCom enabled layout.

## What's Coming Next?
Expansion boards! We're busy preparing the hardware for expansion boards that add on to your base station. We have plans to release the following boards:
- Booster station expansion - turns your FireBox into a dual 5A booster station
- Throttle expansion - turns your FireBox into a self-contained throttle plus booster with integrated LCD.
- LCC expansion - adds layout networking capabilities to your board
- Other layout networking protocols will be supported as demand requires.

## Specifications
- Fully NMRA compliant command station preloaded with upgraded DCC++ firmware
- Main track supplies 5A continuous and 6A peak current with built-in overcurrent limiting, in addition to the software current limiting already built into DCC++
- Programming track supplies 6A peak to the programming track, but is limited in software to NMRA-compliant 250mA.
- 12-24V DC supply power (purchased separately)
- Built-in RailCom detection circuit available on both the main and programming tracks.
- Reverse supply polarity protection to protect your investment
- Easy firmware upgrades over USB
- Control up to 255 locomotives simultaneously
- Microchip SAMD21 ARM Cortex-M0+ processor 
- Espressif ESP8266 WiFi module. 
- Integrated 256K EEPROM chip to save turnout, output, and sensor data.
- Two Sparkfun Qwiic-compatible I2C Headers allow for quick plugging of accessories such as LCDs.
- Expansion headers allow for addition of layout networking expansions to the board, or conversion into a booster station. 

*RailCom is a trademark of Lenz Elektronik GmbH. RailCom is protected by patents in Germany and Austria.*
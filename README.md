ghz\_sig\_gen
===========

The GSG is a laboratory grade modular function generator.
An open-hardware signal generator capable of 1.4GHz output. Based on the Analog
Devices AD9914 DDS IC.

Currently the board will be Easy-PHI compatible, meaning it will leverage the 
Arduino-Due compatible template based on Atmel SAM3X8E. This gives us an 
on-board microcontroller and an easy basic programming interface (USB!).

This document is a work-in-progress as of January 2016. 

The GSG is capable of three modes of operation. 
* ~~In I<sup>2</sup>C mode, the GSG is primarily a breakout for the AD9914. 
  Control is either directly to the AD9914 or via the optional microcontroller 
  for AD9910 emulation.~~ - AD9910 emulation will still be looked at and may involve
  I<sup>2</sup>C. 
* In USB mode, the optional microcontroller can be used to interface with the 
  AD9914 via SPI or the FPGA at the full 32-bit data bus. ~~This mode allows modulation 
  at up to 145 MSPS.~~ - direct from FPGA can theoretically drive 145MSPS however 
  FPGA project will likely be a follow-on separate endeavor. 
* ~~Finally, the optional microcontroller daughterboard can drive a display board 
  for standalone operation.~~  

The physical layout of the GSG adheres to the
[MECB-A](https://github.com/mechanart/mecb) specification which in
turn is based on a Eurocard 3U standard size of 100mm by 160mm. It is used as 
the Local Oscillator in the 
[Mar de Lo Radio](https://github.com/mechanart/mar-de-lo-radio).

The goals of the project are as follows:
* Lowest noise possible (amplitude and phase)
  - Phase noise dependent on REF CLK - see external clock details
  - decoupled DAC Bypass pin, absent from the AD9910, for superior noise 
    performance
* Flexible control 
  - SPI and Parallel modes via direct connections, I<sup>2</sup>C and USB via 
    optional daughterboard microcontroller.
  - Basic control library ported to Arduino IDE (Easy-φ)
* Modular architecture
  - ~~Voltage regulators are connectorized~~
  - Serial and Parallel programming interfaces exposed
* ~~Optional stand-alone capability
  - display (touchscreen expected)
  - control panel
  - onboard microcontroller~~

Additionally, there are some contrived aspects to make this an interesting 
open project:
* Only free development tools required.
  - Atmel (Arduino-compatible) toolchain is free and there are open-source compilers available
  - Schematic and Layout are designed to be compatible with discounted/free 
    versions of many EDA packages:
      - Altium Designer (the native format for this project - should import to CircuitMaker no problem)
      - CircuitMaker
      - Upverter (Altium import)
      - Zuken CadStar Express (300 pin/50 part limit)
      - EAGLE Hobbyist (160x100mm limit, 6 layers)
      - Diptrace (300pin limit, 2 signal layers, support TBD)
      - DesignSpark (TBD)
      - gEDA
      - KiCad (Easy-φ is already in this format, hopefully backporting the design will be easy)

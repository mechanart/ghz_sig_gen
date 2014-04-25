ghz\_sig\_gen
===========

The GSG is a laboratory grade modular function generator.
An open-hardware signal generator capable of 1.4GHz output. Based on the Analog
Devices AD9914 DDS IC.

The GSG is capable of three modes of operation. 
* In I^2C mode, the GSG is primarily a breakout for the AD9914. Control is
  either directly to the AD9914 or via the onboard microcontroller for AD9910
  emulation.
* In USB mode, the microcontroller can be used to interface with the AD9914 via
  the FPGA at the full 32-bit data bus. This mode allows modulation at up to
  145 MSPS.
* Finally, the optional microcontroller daughterboard can drive a display board 
  for standalone operation.  

The physical layout of the GSG adheres to the
[MECB-A](https://github.com/mechanart/mecb) specification which in
turn is based on a Eurocard 3U standard size of 100mm by 160mm. It is used as the
Local Oscillator in the [Mar de Lo Radio](https://github.com/mechanart/mar-de-lo-radio).

The goals of the project are as follows:
* Lowest noise possible (amplitude and phase)
  - Phase noise dependent on REF CLK - see external clock details
* Flexible control 
* Modular architecture
  - Voltage regulators are connectorized
  - Serial and Parallel programming interfaces exposed
* Optional stand-alone capability
  - display
  - control panel
  - onboard microprocessor

Additionally, there are some contrived aspects to make this an interesting 
open project:
* All free development tools required.
  - Cypress and Lattice tools are freely available for download
  - Schematic and Layout are designed to be compatible with discounted/free 
    versions of many EDA packages:
      - Zuken CadStar Express (300 pin/50 part limit)
      - EAGLE Hobbyist (160x100mm limit, 6 layers)
      - Diptrace (300pin limit, 2 signal layers, support TBD)
      - DesignSpark 
      - gEDA
      - KiCad

ghz\_sig\_gen
===========

An open-hardware signal generator capable of 1.4GHz output. Based on the Analog
Devices AD9914 DDS IC.

The GSG is capable of being controlled via serial or parallel links. When driven
by the full 32-bit parallel bus both phase and amplitude can be modulated at
the AD9914's maximum rate of 145 MSPS when used with the optional OCXO.

The physical layout of the GSG adheres to the
[MECB-A](https://github.com/mechanart/mechanart/mecb) specification which in
turn is based on a Eurocard standard size of 100mm by 160mm. It is used as the
LO in the [Mar de Lo Radio](https://github.com/mechanart/mar-de-lo-radio).

The goals of the project are as follows:
* Lowest noise possible
* Flexible control 
* Modular architecture
* Optional stand-alone capability
  - display
  - control panel
  - onboard microprocessor

The GSG is a laboratory grade modular function generator.

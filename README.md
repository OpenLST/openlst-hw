OpenLST Reference Hardware
==========================

This repository contains a KiCad project with a hardware reference
implementation for the OpenLST.  This design is a simplified version
of the Texas Instruments CC1110 432 MHz reference design.  A 1 watt
power amplifier module has been added to increase operating range.
The design is intended for use at 437 MHz, however, it may be modified
for use at other frequencies.

The user is responsible for obtaining and maintaining the necessary
license to operate this radio.  The example project uses frequencies
in the US Amateur Radio UHF band. Transmissions in this band require a
valid FCC license and compliance with CFR Part 97.

![board rendering](images/openlst-hw.jpg)

Contents
--------

This repository contains the following items:

  * [KiCAD 4.0](http://kicad-pcb.org/) project with self-contained part library
  * [Schematic](pdf/openlst-hw.pdf) in PDF form
  * [Bill of materials](bom/) with ordering information for components
  * [Gerber files](gerber/) for PCB fabrication

License & Legal Information
---------------------------

Copyright 2018 Planet Labs Inc. This work is licensed under a
Creative Commons Attribution-ShareAlike 4.0 International License.

This document may contain technology or software the export of which
is or may be restricted by the Export Administration Act and the
Export Administration Regulations (EAR), 15 C.F.R. parts
730-774. Diversion contrary to U.S. law is prohibited.

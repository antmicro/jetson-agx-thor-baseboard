# Jetson AGX Thor Baseboard

Copyright (c) 2025 [Antmicro](https://www.antmicro.com)

## Overview

This project contains open hardware design files for a baseboard supporting NVIDIA Jetson AGX Thor (P5000) System on Module.
The baseboard break-routes common IO-interfaces for typical, desktop usage.
The baseboard also features an FMC-style expansion connector so it is possible to combine it with other baseboards and custom-designed accessories in order to accelerate the development of new Thor-based products. 
The PCB design files were prepared in KiCad 9.x.

## Key features

* 

The Jeston AGX Thor Baseboard has two 50-pin FFC connectors which makes it electrically compatible with a variety of camera modules and video accessories developed by Antmicro. Those are: 

* [GMSL Deserializer Board](https://github.com/antmicro/gmsl-deserializer)
* [SDI-MIPI Video Converter](https://github.com/antmicro/sdi-mipi-video-converter-hw) 
* [HDMI to MIPI CSI-2 Bridge](https://github.com/antmicro/hdmi-mipi-bridge)
* [Composite Video to MIPI CSI-2 Bridge](https://github.com/antmicro/cvbs-mipi-bridge)

## Project structure

The main directory contains KiCad PCB project files, a LICENSE, and a README.
The remaining files are stored in the following directories:
 
* `img` - contains graphics for this README

## Licensing

This project is published under the [Apache-2.0](LICENSE) license.


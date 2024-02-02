[![Build](https://github.com/Kampi/ZSWatch-Dock/actions/workflows/build.yml/badge.svg)](https://github.com/Kampi/ZSWatch-Dock/actions/workflows/build.yml)

# ZSWatch-Dock

## Table of Contents

- [ZSWatch-Dock](#zswatch-dock)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
  - [Configurations](#configurations)
    - [With integrated Segger J-Link](#with-integrated-segger-j-link)
    - [Without integrated Segger J-Link](#without-integrated-segger-j-link)
  - [Directory structure](#directory-structure)
  - [Maintainer](#maintainer)

## About

Programming and charging dock for the [ZSWatch](https://github.com/jakkra/ZSWatch).

![Complete](/docs/images/Dock_Complete.jpg)

Please check the [wiki](https://github.com/jakkra/ZSWatch/wiki) for more information about the project.

## Configurations

The dock can be used with an integrated Segger J-Link debugger or with an external Serial Wire Debugger (SWD) with an [10-pol ARM Cortex JTAG SWD](https://developer.arm.com/documentation/101416/0100/Hardware-Description/Target-Interfaces/Cortex-Debug--10-pin-) connector.

The dock can be used in two configurations:

### With integrated Segger J-Link

![PCB Top side](/docs/images/Preview.png)

The board acts as a USB SWD debugger and no external debugger is needed.

> NOTE: Due to the license the programmer is node-locked to the nRF5340 MCU.

### Without integrated Segger J-Link

![PCB Top side](/docs/images/Preview_WithoutJLink.png)

The board acts as a SWD bridge to connect an external debugger at the `DEBUG` connector with the watch.

## Directory structure

- `cad`: 3D model of the complete PCB
- `docs`: All kind of project documentation
- `project`: KiCad project for the PCB

## Maintainer

- [Daniel Kampert](mailto:daniel.kameprt@kampis-elektroecke.de)
- [Jakob Krantz](mail@jakobkrantz.se)

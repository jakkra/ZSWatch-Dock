# CHANGELOG

## [1.0.4] - 20.07.2024

**Fixed:**

- Fix non ideal footprint for NTS0104GU12

**Added:**

- Add current measurement interface
- Add LM66200 for VBus

**Changed:**

**Removed:**

- Remove protection diode from VBus

## [1.0.3] - 20.07.2024

**Fixed:**

- Fix wrong part number for switching regulator inductor (was 1 uH instead of 10 uH)

**Added:**

- Add QR code with link to GitHub repository
- Add switch to enable / disable charging
- Add workflow for KiBot
- Add additional USB data interface

**Changed:**

- Change PCB color to blue
- Change PCB version to 1.0.3

**Removed:**

- Remove reset line from STM32 to the watch connector

## [1.0.2] - 30.09.2023

**Added:**

- Add jumper to bridge the STM32 processor when not assembled (no license used)
- Add standard STLink V3 connector
- Add dip switch to configure the reset pin for the watch

**Changed:**

- Clean up design
- Change PCB version to 1.0.2

**Removed:**
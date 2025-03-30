# Smart Home Products and Automation Biometric Door lock system using IOT

## Overview
A secure employee access system using dual fingerprint sensors, SMS alerts, and real-time logging.

## Features
- Dual fingerprint authentication (IN/OUT)
- Anti-spoofing with confidence checks
- SMS alerts for access/fake attempts
- SD card logging
- Admin SMS commands (UNLOCK/LOG)

## Components
- Arduino Uno
- R305 Sensors (x2)
- SIM800L GSM Module
- DS1302 RTC
- 4x4 Keypad
- 16x2 I2C LCD

## Wiring
See [schematics/schematic.txt](schematics/schematic.txt).

## Setup
1. Install [Arduino IDE](https://www.arduino.cc/).
2. Clone this repo.
3. Install required libraries:
   - Adafruit Fingerprint Sensor
   - RTClib
   - LiquidCrystal_I2C
   - Keypad
4. Upload `src/SmartHome_Biometric_Lock.ino` to Arduino.

## License
MIT
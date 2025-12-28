timeticksimulator

A programmable fake bomb prop designed for Airsoft games, built using Arduino Nano. This project simulates a countdown timer with arm/disarm mechanics using a keypad and password system.

## Features
* **Countdown Timer:** Programmable hours, minutes, and seconds.
* **Password System:** 4-digit code required to arm and disarm the device.
* **Audio-Visual Feedback:**
    * 16x2 LCD Display (I2C) for status and timer.
    * Buzzer for beep effects (button press, alarm, explosion).
    * LED indicators (Red, Yellow, Green).
* **Penalty Mechanic:** Wrong password entry speeds up the countdown timer.

## Hardware Requirements
* Arduino Nano (ATmega328P)
* 16x2 LCD Display with I2C Module
* 4x3 or 4x4 Matrix Keypad
* Active Buzzer
* LEDs (Red, Yellow, Green)
* Jumper Wires & Breadboard

## Libraries Used
1.  `LiquidCrystal_I2C`
2.  `Keypad`

## How to Use
1.  Power on the device.
2.  Create a 4-digit password.
3.  Set the timer duration.
4.  Press `#` to **ARM** the bomb.
5.  To **DEFUSE**, press `*` and enter the correct password.

---
*Disclaimer: This project is strictly for educational purposes and airsoft/paintball gaming simulations only.*

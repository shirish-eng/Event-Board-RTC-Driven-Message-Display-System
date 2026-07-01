# EventBoard: RTC-Driven Message Display System

I designed and implemented an RTC-driven embedded message display system using the LPC2148 microcontroller. The project integrates the internal RTC, keypad, LCD, and LM35 temperature sensor to demonstrate real-time scheduling, peripheral interfacing, and modular Embedded C development

## Features

* Real-time message display using RTC
* User input through a 4×4 matrix keypad
* 16×2 LCD interface for message and temperature display
* Ambient temperature monitoring using LM35
* Modular Embedded C implementation
* Proteus simulation support

## Hardware

* LPC2148 (ARM7TDMI-S)
* 16×2 Alphanumeric LCD
* 4×4 Matrix Keypad
* LM35 Temperature Sensor

## Software

* Embedded C
* Keil µVision 4
* Proteus

## System Flow

```text
Keypad + LM35 + RTC → LPC2148 → 16×2 LCD
```

## Repository Structure

```text
Source_Code/
Keil_Project/
```

## Future Enhancements

* EEPROM-based event storage
* Multiple scheduled messages
* Alarm and notification support
* IoT-based remote event updates

## Author

**Shirish**
ECE Graduate

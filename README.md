# EventBoard: RTC-Driven Message Display System

An embedded system built on the **LPC2148 (ARM7TDMI-S)** microcontroller that displays scheduled messages based on real-time clock (RTC) data while also monitoring ambient temperature using the **LM35** sensor.

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

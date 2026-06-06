# Arduino Smart Home Security & Leak Detection System

A microcontroller-based security and monitoring system developed using Arduino. This project combines access control, intrusion detection, emergency alerting, and water leak detection into a single integrated alarm system.

The system uses a keypad-protected alarm panel, ultrasonic motion detection, water level monitoring, visual indicators, an LCD display, and audible alarms to simulate a smart home or small business security solution.

* Features

## Access Control System

- Password-protected keypad entry
- LCD status display
- Access granted and denied notifications
- Password verification using a 4-digit PIN
- Passcode reset and retry functionality

## Intrusion Detection

- Ultrasonic distance sensor monitoring
- Configurable detection threshold
- Burglar alarm activation when motion is detected
- Audible buzzer alert
- Visual warning indicators
- Real-time serial monitoring

## Emergency Panic Alarm

- Dedicated panic button
- Instant emergency activation
- Audible alarm and visual alerts
- Emergency message displayed on LCD
- Manual alarm toggle functionality

## Water Leak Detection

- Water level sensor monitoring
- Multiple water level states:
  - Empty
  - Low
  - Medium
  - High
- Leak warning notifications
- Automatic alarm activation on high water levels
- Visual status indicators

## User Interface

- 16x2 LCD display
- 4x4 keypad input
- LED status indicators:
  - Green LED – System Armed
  - Red LED – Alarm Active
  - Blue LED – Warning/Panic Status
- Serial Monitor logging

* Hardware Components

## Microcontroller

- Arduino Mega 2560 (or compatible)

## Input Devices

- 4x4 Matrix Keypad
- Ultrasonic Sensor (HC-SR04)
- Water Level Sensor
- Panic Button
- Arm/Disarm Button

## Output Devices

- 16x2 LCD Display
- Piezo Buzzer
- Green LED
- Red LED
- Blue LED

* System Functions

## Alarm Arming & Disarming

The system can be armed and disarmed using a dedicated control button. When armed, the ultrasonic sensor continuously monitors for movement or proximity changes.

## Password Authentication

Users must enter the correct PIN through the keypad to gain access. Incorrect entries generate an access denied message and prompt another attempt.

## Intrusion Detection

When the system is armed, the ultrasonic sensor measures distance continuously. If an object is detected within the configured threshold, the burglary alarm is activated.

## Panic Mode

A dedicated emergency button instantly triggers an alarm regardless of system state, providing a rapid response mechanism for emergencies.

## Leak Monitoring

The water sensor continuously monitors water levels and categorises readings into different alert states. High water levels trigger a leak warning and activate the alarm system.

* Technologies Used

## Hardware

- Arduino Mega
- HC-SR04 Ultrasonic Sensor
- Water Level Sensor
- 4x4 Matrix Keypad
- 16x2 LCD Display
- LEDs
- Piezo Buzzer

## Software

- Arduino IDE
- C/C++
- LiquidCrystal Library
- Keypad Library

* Key Features Demonstrated

- Embedded Systems Programming
- Sensor Integration
- Event-Driven Programming
- User Authentication
- Alarm System Design
- Real-Time Monitoring
- Hardware Interfacing
- Input Debouncing
- Serial Communication

* Project Objectives

The project aimed to:

- Develop a functional Arduino-based security system
- Implement password-protected access control
- Detect and respond to intrusion events
- Monitor environmental hazards such as water leaks
- Provide visual and audible alert mechanisms
- Integrate multiple sensors into a single system

* Future Improvements

Potential future improvements include:

- RFID authentication support
- GSM/SMS notifications
- Mobile application integration
- Wi-Fi connectivity using ESP8266/ESP32
- Cloud monitoring dashboard
- Multiple user accounts
- Event logging to SD card
- Battery backup system
- Remote arming and disarming

* Author

**Markuss Zakss**  
TUS Midlands – Embedded Systems Project

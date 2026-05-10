# Plant Monitor

Arduino-based soil moisture monitoring system for detecting dry soil conditions.

## Components
- Arduino Uno
- FC-28 Soil Moisture Sensor
- Piezo Buzzer
- LED
- Breadboard
- Jumper Wires

## Features
- Soil moisture monitoring
- Dry soil detection
- LED alert system
- Buzzer notification

## Circuit
The soil moisture sensor is connected to analog pin A0.
The buzzer and LED activate when the soil becomes dry.

## How It Works
The Arduino reads moisture values from the sensor.
When the value exceeds the calibrated threshold, the buzzer sounds and the LED turns on.

## Technologies Used
- Arduino IDE
- Embedded C/C++
- Analog Sensors

## File Structure
- Plant_Monitor.ino
- circuit.png
- demo.mp4
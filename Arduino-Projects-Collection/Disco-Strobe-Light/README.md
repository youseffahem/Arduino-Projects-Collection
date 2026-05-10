# Disco Strobe Light

Arduino-based disco strobe light project using LEDs and a potentiometer to control flashing speed.

## Components
- Arduino Uno
- 4 LEDs
- Potentiometer
- 220Ω Resistors
- Breadboard
- Jumper Wires

## Features
- Alternating LED flashing effect
- Adjustable flashing speed
- Potentiometer-based control

## Circuit
Two red LEDs connect to pin 12.
Two blue LEDs connect to pin 11.
The potentiometer controls the flashing speed through analog input.

## How It Works
The Arduino reads the potentiometer value and maps it to delay timing.
The LEDs flash alternately to create a strobe/disco effect.

## Technologies Used
- Arduino IDE
- Embedded C/C++
- PWM & Analog Input

## File Structure
- Disco_Strobe_Light.ino
- circuit.png
- demo.mp4
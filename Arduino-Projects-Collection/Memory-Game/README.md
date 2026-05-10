# Memory Game

Interactive Arduino memory game using LEDs, push buttons, and sound effects.

## Components
- Arduino Uno
- 4 LEDs
- 4 Push Buttons
- Piezo Buzzer
- Resistors
- Breadboard
- Jumper Wires

## Features
- Random light sequence generation
- User memory challenge
- Sound feedback
- Increasing difficulty levels

## Circuit
Each LED is connected to a digital output pin.
Each push button is connected to an input pin.
A piezo buzzer is used for sound effects and feedback.

## How It Works
The Arduino generates a random LED sequence.
The player must repeat the sequence correctly using the buttons.
If the sequence is wrong, the fail sound and flashing effect are activated.

## Technologies Used
- Arduino IDE
- Embedded C/C++
- Digital Input/Output
- Arrays & Randomization

## File Structure
- Memory_Game.ino
- circuit.png
- demo.mp4
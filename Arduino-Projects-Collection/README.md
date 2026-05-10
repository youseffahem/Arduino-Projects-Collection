<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=00979D&center=true&vCenter=true&width=700&lines=⚡+Arduino+Projects+Collection;Embedded+Systems+%7C+C%2FC%2B%2B+%7C+Hardware+%26+Sensors;Building+Real+Things+with+Real+Code)](https://git.io/typing-svg)

### *Embedded Systems Engineering · Hardware Programming · Sensor Integration*

[![Arduino](https://img.shields.io/badge/Platform-Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)](https://www.arduino.cc/)
[![C++](https://img.shields.io/badge/Language-C%2FC%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)](https://isocpp.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Projects](https://img.shields.io/badge/Projects-5-orange?style=for-the-badge)]()
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)]()

<br>

> *A curated collection of hands-on Arduino and embedded systems projects covering hardware control, sensor integration, PWM signal management, and interactive game logic — built to demonstrate practical embedded engineering skills.*

<br>

---

</div>

## 📖 Introduction

Welcome to my **Arduino Projects Collection** — a portfolio of embedded systems projects built using the **Arduino platform**, **Embedded C/C++**, and a range of electronic components and sensors.

Each project targets a specific concept in embedded development: from basic button-controlled GPIO, to PWM-based dimming, analog sensor reading, and multi-component game logic. These are honest learning projects that reflect my progression as a **Computer Science student specializing in Embedded Systems** — built, tested, and documented on real hardware.

Every project folder is self-contained and includes the full Arduino source code (`.ino`), a circuit image, a recorded demo video, and an animated GIF — making it easy to review each project without setting up the hardware.

<br>

---

## 🚀 Featured Project

<div align="center">

### 🧠 Memory Game — Simon Says on Arduino

> The most complete project in this collection: a Simon Says-style memory game with growing LED sequences, button input, buzzer feedback, and win/loss detection — all implemented in embedded C on a bare Arduino board.

![Memory Game Demo](Memory-Game/demo.gif)

*[Jump to full project details ↓](#-04---memory-game)*

</div>

<br>

---

## 📂 Repository Overview

```
Arduino-Projects-Collection/
│
├── 📁 Controlled-LED/
│   ├── Controlled_LED.ino
│   ├── circuit.png
│   └── demo.gif
│
├── 📁 Disco-Strobe-Light/
│   ├── Disco_Strobe_Light.ino
│   ├── circuit.png
│   └── demo.gif
│
├── 📁 Light-Dimmer/
│   ├── Light_Dimmer.ino
│   ├── circuit.png
│   └── demo.gif
│
├── 📁 Memory-Game/
│   ├── Memory_Game.ino
│   ├── circuit.png
│   └── demo.gif
│
├── 📁 Plant-Monitor/
│   ├── Plant_Monitor.ino
│   ├── circuit.png
│   └── demo.gif
│
└── README.md
```

<br>

---

## 🛠️ Technologies & Tools

<div align="center">

| Category | Details |
|:---|:---|
| 🖥️ **Microcontroller** | Arduino Uno / Nano / Mega |
| 💻 **IDE** | Arduino IDE 2.x |
| 🔤 **Language** | Embedded C / C++ |
| 📡 **Communication** | Serial Monitor (UART) |
| ⚡ **Techniques** | PWM, Digital I/O, Analog Read, Button Polling |
| 🔬 **Sensors** | Soil Moisture Sensor, Photoresistor (LDR) |
| 💡 **Actuators** | LEDs, Buzzers, Push Buttons |
| 🔌 **Electronics** | Resistors, Capacitors, Breadboard, Jumper Wires |
| 📐 **Circuit Design** | Schematic design & prototyping |

</div>

<br>

---

## 🚀 Project Showcase

<div align="center">

| # | Project | Description | Key Concepts | Difficulty |
|:--:|:---|:---|:---|:--:|
| 01 | 💡 [Controlled LED](#-01---controlled-led) | Precise LED control via digital output | Digital I/O, GPIO | ⭐ |
| 02 | 🪩 [Disco Strobe Light](#-02---disco-strobe-light) | Rapid multi-LED strobe sequencing | Timing, Loops, Arrays | ⭐⭐ |
| 03 | 🔆 [Light Dimmer](#-03---light-dimmer) | Smooth LED brightness via PWM | PWM, analogWrite | ⭐⭐ |
| 04 | 🧠 [Memory Game](#-04---memory-game) | Simon-style pattern recall game | Logic, Arrays, UX | ⭐⭐⭐ |
| 05 | 🌱 [Plant Monitor](#-05---plant-monitor) | Soil moisture sensing with alerts | Sensors, Automation | ⭐⭐⭐ |

</div>

<br>

---

## 📋 Project Details

---

### 💡 01 - Controlled LED

> **Category:** Digital Input & Output | GPIO Control

A foundational project demonstrating LED control through a **push button input**. When the button is pressed, the Arduino reads the digital input signal and toggles the LED on or off accordingly — reinforcing the core input/output relationship at the heart of embedded systems programming.

**Concepts Demonstrated:**
- `pinMode()`, `digitalRead()`, and `digitalWrite()` functions
- Digital input reading and output switching
- Button state detection in the main loop
- Setup/loop firmware architecture

**Circuit Preview:**

![Circuit](Controlled-LED/circuit.png)

**Animated Demo:**

![Demo](Controlled-LED/demo.gif)

---

### 🪩 02 - Disco Strobe Light

> **Category:** LED Sequencing | Timing Control

An energetic multi-LED strobe sequencer that rapidly cycles through light patterns, simulating a disco strobe effect. This project demonstrates array-based LED management, precise microsecond-level timing, and the use of loops to produce dynamic lighting sequences.

**Concepts Demonstrated:**
- LED array management
- High-frequency strobe timing (`delayMicroseconds`)
- Pattern sequencing with `for` loops
- Non-blocking delay techniques

**Circuit Preview:**

![Circuit](Disco-Strobe-Light/circuit.png)

**Animated Demo:**

![Demo](Disco-Strobe-Light/demo.gif)

---

### 🔆 03 - Light Dimmer

> **Category:** PWM | Analog Output

A hardware-level light dimmer that uses **Pulse Width Modulation (PWM)** to achieve smooth, continuous control of LED brightness. Brightness levels are controlled via a potentiometer, with the analog input mapped to PWM output values in real time — demonstrating core embedded signal processing.

**Concepts Demonstrated:**
- PWM signal generation with `analogWrite()`
- Analog input reading with `analogRead()`
- Input-to-output value mapping (`map()` function)
- Real-time signal adjustment

**Circuit Preview:**

![Circuit](Light-Dimmer/circuit.png)

**Animated Demo:**

![Demo](Light-Dimmer/demo.gif)

---

### 🧠 04 - Memory Game

> **Category:** Game Logic | Interactive Systems

A fully interactive **Simon Says**-style memory game implemented entirely in embedded C on Arduino. The system generates and displays a growing LED sequence that the player must reproduce using push buttons. Includes difficulty escalation, win/loss detection, and audio feedback via a buzzer.

**Concepts Demonstrated:**
- State machine design
- Random sequence generation
- Button debouncing
- Multi-LED and buzzer coordination
- Game loop logic and user interaction

**Circuit Preview:**

![Circuit](Memory-Game/circuit.png)

**Animated Demo:**

![Demo](Memory-Game/demo.gif)

---

### 🌱 05 - Plant Monitor

> **Category:** Sensor Integration | Embedded Automation

An automated plant health monitoring system that reads **soil moisture levels** using an analog capacitive sensor and triggers an alert (LED indicator + buzzer) when soil moisture drops below a defined threshold. Data is also streamed to the Serial Monitor for real-time observation.

**Concepts Demonstrated:**
- Analog sensor integration
- Threshold-based decision logic
- Serial communication for data logging
- Embedded automation using polling-based sensor reads

**Circuit Preview:**

![Circuit](Plant-Monitor/circuit.png)

**Animated Demo:**

![Demo](Plant-Monitor/demo.gif)

---

## 🧰 Hardware Components Used

<div align="center">

| Component | Purpose |
|:---|:---|
| Arduino Uno / Nano | Main microcontroller board |
| LEDs (various colors) | Visual output and indicators |
| Push Buttons | User input and game interaction |
| Potentiometer (10kΩ) | Analog input for light dimming |
| Soil Moisture Sensor | Plant hydration monitoring |
| Passive Buzzer | Audio feedback and alerts |
| Resistors (220Ω, 10kΩ) | Current limiting and pull-down |
| Breadboard | Prototyping and circuit assembly |
| Jumper Wires | Component interconnection |
| USB Cable (Type-B) | Power delivery and serial communication |

</div>

<br>

---

## 💻 Software Used

<div align="center">

| Tool | Purpose |
|:---|:---|
| [Arduino IDE 2.x](https://www.arduino.cc/en/software) | Primary development environment |
| Arduino Serial Monitor | Real-time sensor data logging |
| Fritzing / Tinkercad | Circuit schematic design |
| OBS Studio | Demo video recording |
| GIMP / ScreenToGif | Animated GIF generation |

</div>

<br>

---

## 🎯 Skills Demonstrated

```
✅ Embedded C/C++ Programming       ✅ PWM Signal Control
✅ GPIO Digital & Analog I/O        ✅ Sensor Integration & Calibration
✅ Real-Time System Design          ✅ State Machine Implementation
✅ Hardware Debugging & Prototyping ✅ Serial Communication (UART)
✅ Circuit Design & Assembly        ✅ Button Input & Polling Logic
✅ Component Datasheet Reading      ✅ Embedded Automation
```

<br>

---

## 📸 Screenshots

<div align="center">

| Controlled LED | Disco Strobe | Light Dimmer |
|:---:|:---:|:---:|
| ![](Controlled-LED/circuit.png) | ![](Disco-Strobe-Light/circuit.png) | ![](Light-Dimmer/circuit.png) |

| Memory Game | Plant Monitor |
|:---:|:---:|
| ![](Memory-Game/circuit.png) | ![](Plant-Monitor/circuit.png) |

</div>

<br>

---

## 🎬 Animated GIF Demos

<div align="center">

**💡 Controlled LED**
![Controlled LED Demo](Controlled-LED/demo.gif)

---

**🪩 Disco Strobe Light**
![Disco Strobe Demo](Disco-Strobe-Light/demo.gif)

---

**🔆 Light Dimmer**
![Light Dimmer Demo](Light-Dimmer/demo.gif)

---

**🧠 Memory Game**
![Memory Game Demo](Memory-Game/demo.gif)

---

**🌱 Plant Monitor**
![Plant Monitor Demo](Plant-Monitor/demo.gif)

</div>

<br>

---

## 🎓 Learning Outcomes

Through building and documenting these projects, the following practical skills were developed and reinforced:

- **Embedded Programming Fundamentals** — Writing clean firmware in C/C++ for microcontrollers with limited RAM and flash, following the setup/loop structure of the Arduino runtime.
- **PWM & Analog Signal Control** — Using `analogWrite()` and `analogRead()` to bridge the gap between digital microcontrollers and analog real-world signals.
- **Sensor-Driven Automation** — Reading raw analog sensor values and acting on them through threshold comparisons to drive output peripherals.
- **State Machine Design** — Structuring interactive systems like the Memory Game into clearly defined states with predictable transitions and clean logic flow.
- **Hardware Debugging** — Diagnosing issues where software behavior and physical circuit conditions interact — a core embedded systems skill.
- **Technical Documentation** — Producing circuit diagrams, commented source code, and multimedia project walkthroughs suitable for portfolio and professional review.

<br>

---

## 🔭 Future Improvements

- [ ] 🌐 Migrate the Plant Monitor to an **ESP32** for Wi-Fi connectivity and cloud data logging
- [ ] 📱 Add a **Bluetooth serial interface** to the Memory Game for score tracking on a phone
- [ ] 📊 Integrate an **OLED display (SSD1306)** into the Plant Monitor for local readout
- [ ] ⏱️ Refactor timing-sensitive code to use `millis()` instead of `delay()` for non-blocking logic
- [ ] 🧪 Add basic **software testing** with assertion checks via Serial output
- [ ] 🏗️ Design simple **PCB layouts** using EasyEDA for a cleaner, breadboard-free version
- [ ] 🌡️ Extend the Plant Monitor with a **DHT11 temperature/humidity sensor** for richer data

<br>

---

## 📬 Contact

<div align="center">

Feel free to reach out for collaboration, questions, or professional opportunities.

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/youseffahem)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yousef-fahem/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yousef.fahem11@gmail.com)

</div>

<br>

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=youseffahem&show_icons=true&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=youseffahem&layout=compact&theme=tokyonight&hide_border=true)

</div>

<br>

---

<div align="center">

### ⭐ If you found this repository useful, please consider giving it a star!

*Built with curiosity, a soldering iron, and a lot of Serial.println() debugging.*

<br>

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=youseffahem.Arduino-Projects-Collection)

---



</div>
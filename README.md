<div align="center">

<img src="assets/lab/status-bar.svg" width="100%" alt="Lab status: online, Arduino active, sensors connected, signal flowing, powered">

<img src="assets/lab/arduino-board.svg" width="100%" alt="Animated Arduino Uno board: power LED breathing, pin 13 blinking, TX/RX flickering and signal pulses travelling out along the traces to the LED, buzzer, sensor and button">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=00979D&center=true&vCenter=true&width=700&lines=⚡+Arduino+Projects+Collection;Embedded+Systems+%7C+C%2FC%2B%2B+%7C+Hardware+%26+Sensors;Building+Real+Things+with+Real+Code)](https://github.com/DenverCoder1/readme-typing-svg)

### *Embedded Systems Engineering · Hardware Programming · Sensor Integration*

[![Arduino](https://img.shields.io/badge/Platform-Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)](https://www.arduino.cc/)
[![C++](https://img.shields.io/badge/Language-C%2FC%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)](https://isocpp.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](https://opensource.org/licenses/MIT)
![Projects](https://img.shields.io/badge/Projects-5-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

<img src="assets/lab/power-flow.svg" width="100%" alt="Power flows to the Arduino, then to signal, then to output">

<br>

> *A curated collection of hands-on Arduino and embedded systems projects covering hardware control, sensor integration, PWM signal management, and interactive game logic — built to demonstrate practical embedded engineering skills.*

<br>

<img src="assets/lab/divider-trace.svg" width="100%" alt="">

</div>

## 📖 Introduction

<div align="center">
<img src="assets/lab/boot-sequence.svg" width="82%" alt="System initialisation sequence: boot, GPIO, PWM timers, ADC and UART each report OK, then the lab comes online">
</div>

Welcome to my **Arduino Projects Collection** — a portfolio of embedded systems projects built using the **Arduino platform**, **Embedded C/C++**, and a range of electronic components and sensors.

Each project targets a specific concept in embedded development: from basic button-controlled GPIO, to PWM-based dimming, analog sensor reading, and multi-component game logic. These are honest learning projects that reflect my progression as a **Computer Science student specializing in Embedded Systems** — built, tested, and documented on real hardware.

Every project folder is self-contained and includes the full Arduino source code (`.ino`), a circuit image, a recorded demo video, and an animated GIF — making it easy to review each project without setting up the hardware.

<div align="center">
<img src="assets/lab/signal-gpio.svg" width="100%" alt="">
</div>

---

## 🚀 Featured Project

<div align="center">

### 🧠 Memory Game — Simon Says on Arduino

<img src="assets/lab/motif-memory-game.svg" width="72%" alt="Four LEDs play a growing Simon sequence, the player input line waits, then the sequence grows by one">

> The most complete project in this collection: a Simon Says-style memory game with growing LED sequences, button input, buzzer feedback, and win/loss detection — all implemented in embedded C on a bare Arduino board.

**▶ [Watch the live hardware feed ↓](#-live-lab-experiments)**  ·  *[Jump to full project details ↓](#-04---memory-game)*

<img src="assets/lab/divider-trace.svg" width="100%" alt="">

</div>

## 📂 Repository Overview

```
Arduino-Projects-Collection/
│
├── 📁 assets/
│   └── 📁 lab/                     ← animated lab visuals used by this README
│
├── 📁 Arduino-Projects-Collection/
│   │
│   ├── 📁 Controlled-LED/
│   │   ├── Controlled_LED.ino
│   │   ├── circuit.png
│   │   ├── demo.gif
│   │   └── README.md
│   │
│   ├── 📁 Disco-Strobe-Light/
│   │   ├── Disco_Strobe_Light.ino
│   │   ├── circuit.png
│   │   ├── demo.gif
│   │   └── README.md
│   │
│   ├── 📁 Light-Dimmer/
│   │   ├── Light_Dimmer.ino
│   │   ├── circuit.png
│   │   ├── demo.gif
│   │   └── README.md
│   │
│   ├── 📁 Memory-Game/
│   │   ├── Memory_Game.ino
│   │   ├── circuit.png
│   │   ├── demo.gif
│   │   └── README.md
│   │
│   └── 📁 Plant-Monitor/
│       ├── Plant_Monitor.ino
│       ├── circuit.png
│       ├── demo.gif
│       └── README.md
│
└── README.md
```

<div align="center">
<img src="assets/lab/signal-uart.svg" width="100%" alt="">
</div>

---

## 🧰 The Workbench

<div align="center">

<img src="assets/lab/workbench.svg" width="100%" alt="Virtual electronics workbench: an Arduino wired through a breadboard to a sensor, an LED and a buzzer, with current animating along every wire">

</div>

---

## 🛠️ Technologies & Tools

<div align="center">

<img src="assets/lab/component-strip.svg" width="100%" alt="">

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

<div align="center">
<img src="assets/lab/divider-trace.svg" width="100%" alt="">
</div>

---

## 🚀 Project Showcase

<div align="center">

<img src="assets/lab/power-flow.svg" width="100%" alt="">

| # | Project | Description | Key Concepts | Difficulty |
|:--:|:---|:---|:---|:--:|
| 01 | 💡 [Controlled LED](#-01---controlled-led) | Precise LED control via digital output | Digital I/O, GPIO | ⭐ |
| 02 | 🪩 [Disco Strobe Light](#-02---disco-strobe-light) | Rapid multi-LED strobe sequencing | Timing, Loops, Arrays | ⭐⭐ |
| 03 | 🔆 [Light Dimmer](#-03---light-dimmer) | Smooth LED brightness via PWM | PWM, analogWrite | ⭐⭐ |
| 04 | 🧠 [Memory Game](#-04---memory-game) | Simon-style pattern recall game | Logic, Arrays, UX | ⭐⭐⭐ |
| 05 | 🌱 [Plant Monitor](#-05---plant-monitor) | Soil moisture sensing with alerts | Sensors, Automation | ⭐⭐⭐ |

</div>

<div align="center">
<img src="assets/lab/divider-trace.svg" width="100%" alt="">
</div>

---

## 📋 Project Details

---

### 💡 01 - Controlled LED

<div align="center">
<img src="assets/lab/motif-controlled-led.svg" width="66%" alt="A button press sends a pulse through the microcontroller and lights an LED">
</div>

> **Category:** Digital Input & Output | GPIO Control

A foundational project demonstrating LED control through a **push button input**. When the button is pressed, the Arduino reads the digital input signal and toggles the LED on or off accordingly — reinforcing the core input/output relationship at the heart of embedded systems programming.

**Concepts Demonstrated:**
- `pinMode()`, `digitalRead()`, and `digitalWrite()` functions
- Digital input reading and output switching
- Button state detection in the main loop
- Setup/loop firmware architecture

**Circuit Preview:**

<div align="center">
<img src="assets/lab/panel-rail.svg" width="76%" alt="">
<br>
<sub><b>EXP-01</b> · CONTROLLED LED · 🟢 <b>MOUNTED</b></sub>
<br><br>
<img src="Arduino-Projects-Collection/Controlled-LED/circuit.png" width="76%" alt="Controlled LED circuit">
<br>
<img src="assets/lab/panel-rail.svg" width="76%" alt="">
</div>

**Live Demo:** 🔴 [Open the hardware feed for this experiment ↓](#-live-lab-experiments)

<div align="center">
<img src="assets/lab/signal-gpio.svg" width="100%" alt="">
</div>

---

### 🪩 02 - Disco Strobe Light

<div align="center">
<img src="assets/lab/motif-disco-strobe.svg" width="66%" alt="A potentiometer sets the rate at which two LEDs strobe alternately">
</div>

> **Category:** LED Sequencing | Timing Control

An energetic multi-LED strobe sequencer that rapidly cycles through light patterns, simulating a disco strobe effect. This project demonstrates array-based LED management, precise microsecond-level timing, and the use of loops to produce dynamic lighting sequences.

**Concepts Demonstrated:**
- LED array management
- High-frequency strobe timing (`delayMicroseconds`)
- Pattern sequencing with `for` loops
- Non-blocking delay techniques

**Circuit Preview:**

<div align="center">
<img src="assets/lab/panel-rail.svg" width="76%" alt="">
<br>
<sub><b>EXP-02</b> · DISCO STROBE LIGHT · 🟢 <b>MOUNTED</b></sub>
<br><br>
<img src="Arduino-Projects-Collection/Disco-Strobe-Light/circuit.png" width="76%" alt="Disco Strobe Light circuit">
<br>
<img src="assets/lab/panel-rail.svg" width="76%" alt="">
</div>

**Live Demo:** 🔴 [Open the hardware feed for this experiment ↓](#-live-lab-experiments)

<div align="center">
<img src="assets/lab/divider-trace.svg" width="100%" alt="">
</div>

---

### 🔆 03 - Light Dimmer

<div align="center">
<img src="assets/lab/motif-light-dimmer.svg" width="66%" alt="A potentiometer sweeps the PWM duty cycle and the LED brightness follows">
</div>

> **Category:** PWM | Analog Output

A hardware-level light dimmer that uses **Pulse Width Modulation (PWM)** to achieve smooth, continuous control of LED brightness. Brightness levels are controlled via a potentiometer, with the analog input mapped to PWM output values in real time — demonstrating core embedded signal processing.

**Concepts Demonstrated:**
- PWM signal generation with `analogWrite()`
- Analog input reading with `analogRead()`
- Input-to-output value mapping (`map()` function)
- Real-time signal adjustment

**Circuit Preview:**

<div align="center">
<img src="assets/lab/panel-rail.svg" width="76%" alt="">
<br>
<sub><b>EXP-03</b> · LIGHT DIMMER · 🟢 <b>MOUNTED</b></sub>
<br><br>
<img src="Arduino-Projects-Collection/Light-Dimmer/circuit.png" width="76%" alt="Light Dimmer circuit">
<br>
<img src="assets/lab/panel-rail.svg" width="76%" alt="">
</div>

**Live Demo:** 🔴 [Open the hardware feed for this experiment ↓](#-live-lab-experiments)

<div align="center">
<img src="assets/lab/signal-pwm.svg" width="100%" alt="">
</div>

---

### 🧠 04 - Memory Game

<div align="center">
<img src="assets/lab/motif-memory-game.svg" width="72%" alt="Four LEDs play a growing Simon sequence, the player input line waits, then the sequence grows by one">
</div>

> **Category:** Game Logic | Interactive Systems

A fully interactive **Simon Says**-style memory game implemented entirely in embedded C on Arduino. The system generates and displays a growing LED sequence that the player must reproduce using push buttons. Includes difficulty escalation, win/loss detection, and audio feedback via a buzzer.

**Concepts Demonstrated:**
- State machine design
- Random sequence generation
- Button debouncing
- Multi-LED and buzzer coordination
- Game loop logic and user interaction

**Circuit Preview:**

<div align="center">
<img src="assets/lab/panel-rail.svg" width="76%" alt="">
<br>
<sub><b>EXP-04</b> · MEMORY GAME · 🟢 <b>MOUNTED</b> · ⭐ <b>FEATURED</b></sub>
<br><br>
<img src="Arduino-Projects-Collection/Memory-Game/circuit.png" width="76%" alt="Memory Game circuit">
<br>
<img src="assets/lab/panel-rail.svg" width="76%" alt="">
</div>

**Live Demo:** 🔴 [Open the hardware feed for this experiment ↓](#-live-lab-experiments)

<div align="center">
<img src="assets/lab/divider-trace.svg" width="100%" alt="">
</div>

---

### 🌱 05 - Plant Monitor

<div align="center">
<img src="assets/lab/motif-plant-monitor.svg" width="66%" alt="Soil moisture falls past an alert threshold, firing the LED and buzzer, then recovers after watering">
</div>

> **Category:** Sensor Integration | Embedded Automation

An automated plant health monitoring system that reads **soil moisture levels** using an analog capacitive sensor and triggers an alert (LED indicator + buzzer) when soil moisture drops below a defined threshold. Data is also streamed to the Serial Monitor for real-time observation.

**Concepts Demonstrated:**
- Analog sensor integration
- Threshold-based decision logic
- Serial communication for data logging
- Embedded automation using polling-based sensor reads

**Circuit Preview:**

<div align="center">
<img src="assets/lab/panel-rail.svg" width="76%" alt="">
<br>
<sub><b>EXP-05</b> · PLANT MONITOR · 🟢 <b>MOUNTED</b></sub>
<br><br>
<img src="Arduino-Projects-Collection/Plant-Monitor/circuit.png" width="76%" alt="Plant Monitor circuit">
<br>
<img src="assets/lab/panel-rail.svg" width="76%" alt="">
</div>

**Live Demo:** 🔴 [Open the hardware feed for this experiment ↓](#-live-lab-experiments)

<div align="center">
<img src="assets/lab/signal-sensor.svg" width="100%" alt="">
</div>

---

## 📟 Serial Monitor

<div align="center">

<img src="assets/lab/serial-monitor.svg" width="86%" alt="A serial monitor window with example initialisation output streaming in line by line">

<sub>*Decorative panel — example output shown for illustration, not a capture of live project data.*</sub>

</div>

---

## 🔬 Lab Instruments

<div align="center">

<img src="assets/lab/oscilloscope.svg" width="86%" alt="An oscilloscope screen with a sweeping beam tracing a digital square wave on channel one and an analog waveform on channel two">

<sub>*Decorative instrument panel — waveforms are illustrative, not measured from the projects.*</sub>

<img src="assets/lab/signal-analog.svg" width="100%" alt="">

</div>

---

## 🧰 Hardware Components Used

<div align="center">

<img src="assets/lab/component-strip.svg" width="100%" alt="">

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

<img src="assets/lab/divider-trace.svg" width="100%" alt="">

</div>

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

<div align="center">
<img src="assets/lab/signal-uart.svg" width="100%" alt="">
</div>

---

## 🖼️ Lab Workbench Wall

<div align="center">

<img src="assets/lab/status-bar.svg" width="100%" alt="">

<table>
<tr>
<td align="center" width="33%">
<img src="assets/lab/panel-rail.svg" width="100%" alt=""><br>
<sub><b>EXP-01</b> · CONTROLLED LED</sub><br>
<sub>🟢 MOUNTED · GPIO</sub><br><br>
<img src="Arduino-Projects-Collection/Controlled-LED/circuit.png" width="100%" alt="Controlled LED circuit"><br>
<img src="assets/lab/panel-rail.svg" width="100%" alt="">
</td>
<td align="center" width="33%">
<img src="assets/lab/panel-rail.svg" width="100%" alt=""><br>
<sub><b>EXP-02</b> · DISCO STROBE</sub><br>
<sub>🟢 MOUNTED · TIMING</sub><br><br>
<img src="Arduino-Projects-Collection/Disco-Strobe-Light/circuit.png" width="100%" alt="Disco Strobe Light circuit"><br>
<img src="assets/lab/panel-rail.svg" width="100%" alt="">
</td>
<td align="center" width="33%">
<img src="assets/lab/panel-rail.svg" width="100%" alt=""><br>
<sub><b>EXP-03</b> · LIGHT DIMMER</sub><br>
<sub>🟡 MOUNTED · PWM</sub><br><br>
<img src="Arduino-Projects-Collection/Light-Dimmer/circuit.png" width="100%" alt="Light Dimmer circuit"><br>
<img src="assets/lab/panel-rail.svg" width="100%" alt="">
</td>
</tr>
<tr>
<td align="center" width="33%">
<img src="assets/lab/panel-rail.svg" width="100%" alt=""><br>
<sub><b>EXP-04</b> · MEMORY GAME</sub><br>
<sub>🔵 MOUNTED · ⭐ FEATURED</sub><br><br>
<img src="Arduino-Projects-Collection/Memory-Game/circuit.png" width="100%" alt="Memory Game circuit"><br>
<img src="assets/lab/panel-rail.svg" width="100%" alt="">
</td>
<td align="center" width="33%">
<img src="assets/lab/panel-rail.svg" width="100%" alt=""><br>
<sub><b>EXP-05</b> · PLANT MONITOR</sub><br>
<sub>🟢 MOUNTED · SENSOR</sub><br><br>
<img src="Arduino-Projects-Collection/Plant-Monitor/circuit.png" width="100%" alt="Plant Monitor circuit"><br>
<img src="assets/lab/panel-rail.svg" width="100%" alt="">
</td>
<td align="center" width="33%">
<img src="assets/lab/component-strip.svg" width="100%" alt=""><br>
<sub><b>BENCH</b> · COMPONENT TRAY</sub><br>
<sub>⚡ POWERED · 5 UNITS ONLINE</sub>
</td>
</tr>
</table>

<img src="assets/lab/divider-trace.svg" width="100%" alt="">

</div>

---

## 🔴 Live Lab Experiments

<div align="center">

<sub>*Recorded hardware demonstrations — each feed below is real footage of the circuit running.*</sub>

<br><br>

<img src="assets/lab/live-feed.svg" width="320" alt="Live recording indicator">

**EXPERIMENT 01 · 💡 CONTROLLED LED** — `STATUS: RUNNING`

<img src="Arduino-Projects-Collection/Controlled-LED/demo.gif" width="620" loading="lazy" alt="Controlled LED hardware demo">

<img src="assets/lab/panel-rail.svg" width="620" alt="">

<br>

<img src="assets/lab/live-feed.svg" width="320" alt="Live recording indicator">

**EXPERIMENT 02 · 🪩 DISCO STROBE LIGHT** — `STATUS: RUNNING`

<img src="Arduino-Projects-Collection/Disco-Strobe-Light/demo.gif" width="620" loading="lazy" alt="Disco Strobe Light hardware demo">

<img src="assets/lab/panel-rail.svg" width="620" alt="">

<br>

<img src="assets/lab/live-feed.svg" width="320" alt="Live recording indicator">

**EXPERIMENT 03 · 🔆 LIGHT DIMMER** — `STATUS: RUNNING`

<img src="Arduino-Projects-Collection/Light-Dimmer/demo.gif" width="620" loading="lazy" alt="Light Dimmer hardware demo">

<img src="assets/lab/panel-rail.svg" width="620" alt="">

<br>

<img src="assets/lab/live-feed.svg" width="320" alt="Live recording indicator">

**EXPERIMENT 04 · 🧠 MEMORY GAME** — `STATUS: RUNNING` · ⭐ **FEATURED**

<img src="Arduino-Projects-Collection/Memory-Game/demo.gif" width="620" loading="lazy" alt="Memory Game hardware demo">

<img src="assets/lab/panel-rail.svg" width="620" alt="">

<br>

<img src="assets/lab/live-feed.svg" width="320" alt="Live recording indicator">

**EXPERIMENT 05 · 🌱 PLANT MONITOR** — `STATUS: RUNNING`

<img src="Arduino-Projects-Collection/Plant-Monitor/demo.gif" width="620" loading="lazy" alt="Plant Monitor hardware demo">

<img src="assets/lab/panel-rail.svg" width="620" alt="">

<br>

<img src="assets/lab/power-flow.svg" width="100%" alt="">

</div>

---

## 🎓 Learning Outcomes

Through building and documenting these projects, the following practical skills were developed and reinforced:

- **Embedded Programming Fundamentals** — Writing clean firmware in C/C++ for microcontrollers with limited RAM and flash, following the setup/loop structure of the Arduino runtime.
- **PWM & Analog Signal Control** — Using `analogWrite()` and `analogRead()` to bridge the gap between digital microcontrollers and analog real-world signals.
- **Sensor-Driven Automation** — Reading raw analog sensor values and acting on them through threshold comparisons to drive output peripherals.
- **State Machine Design** — Structuring interactive systems like the Memory Game into clearly defined states with predictable transitions and clean logic flow.
- **Hardware Debugging** — Diagnosing issues where software behavior and physical circuit conditions interact — a core embedded systems skill.
- **Technical Documentation** — Producing circuit diagrams, commented source code, and multimedia project walkthroughs suitable for portfolio and professional review.

<div align="center">
<img src="assets/lab/signal-analog.svg" width="100%" alt="">
</div>

---

## 🔭 Future Improvements

- [ ] 🌐 Migrate the Plant Monitor to an **ESP32** for Wi-Fi connectivity and cloud data logging
- [ ] 📱 Add a **Bluetooth serial interface** to the Memory Game for score tracking on a phone
- [ ] 📊 Integrate an **OLED display (SSD1306)** into the Plant Monitor for local readout
- [ ] ⏱️ Refactor timing-sensitive code to use `millis()` instead of `delay()` for non-blocking logic
- [ ] 🧪 Add basic **software testing** with assertion checks via Serial output
- [ ] 🏗️ Design simple **PCB layouts** using EasyEDA for a cleaner, breadboard-free version
- [ ] 🌡️ Extend the Plant Monitor with a **DHT11 temperature/humidity sensor** for richer data

<div align="center">
<img src="assets/lab/divider-trace.svg" width="100%" alt="">
</div>

---

## 📬 Contact

<div align="center">

Feel free to reach out for collaboration, questions, or professional opportunities.

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/youseffahem)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yousef-fahem/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yousef.fahem11@gmail.com)

<img src="assets/lab/power-flow.svg" width="100%" alt="">

</div>

---

<div align="center">

<img src="assets/lab/footer-lab.svg" width="100%" alt="Lab status active, systems still running">

### ⭐ If you found this repository useful, please consider giving it a star!

*Built with curiosity, a soldering iron, and a lot of Serial.println() debugging.*

<br>

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=youseffahem.Arduino-Projects-Collection)

<img src="assets/lab/status-bar.svg" width="100%" alt="">

</div>

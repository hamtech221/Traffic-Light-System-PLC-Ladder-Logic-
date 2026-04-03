# 🚦 PLC Traffic Light Control System

## 📌 Overview

This project implements an **industrial traffic light control system** using a **Siemens PLC** programmed in ladder logic. The system simulates real-world traffic signal operation using push buttons as inputs and LEDs as outputs.

---

## ⚙️ Tools & Technologies

* **PLC:** Siemens S7-200 / S7-1200
* **Software:** STEP 7 MicroWIN
* **Programming Language:** Ladder Logic (LAD)

---

## 🧠 Working Principle

The traffic light operates in a fixed sequence:

1. 🔴 **Red ON** → Vehicles stop
2. 🟡 **Yellow ON** → Transition phase
3. 🟢 **Green ON** → Vehicles move

Timers are used to control the delay between each state, ensuring smooth and realistic operation.

---

## 🔌 Hardware Abstraction

Push buttons and LEDs are used to simulate real-world traffic signals.
The LED represents the traffic light states (Red and Green), cycling continuously.


---
## 🔌 Inputs & Outputs

### Inputs

* Push Button → Start / Stop control

### Outputs

* Red LED
* Yellow LED
* Green LED

---

## 🔄 Features

* Timer-based sequential control
* Real-world traffic signal simulation
* Structured and modular ladder logic design
* Easy to expand for multi-road intersections

---

## 🎥 Demonstration

[▶ Watch Demo](https://github.com/user-attachments/assets/eb6d274e-520d-413c-8fa5-d4311e1fcf14)

---

## 📂 Repository Contents

* PLC Program File
* Project Documentation
* Demo Video

---
## 📁 Project Files

- `TRAFFIC_LIGHT.mwp` → Complete Siemens PLC project (open in STEP 7 / MicroWIN)
- `TRAFFIC.awl` → Instruction List (AWL/STL) representation of the control logic
---

## 🚀 Future Improvements

* Multi-lane traffic control system
* Pedestrian crossing integration
* Sensor-based adaptive timing
* Fault detection and alarms

---


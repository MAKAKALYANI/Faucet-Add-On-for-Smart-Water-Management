

# 🚰 Faucet Add-On for Smart Water Management

An Arduino-based smart device that monitors and limits household water usage using a dual-mode system (Running Mode and Filling Mode) with real-time sensing and alerts.

---

## 📌 Project Overview

To address the global water crisis, this project introduces a **low-cost, sensor-based faucet add-on** that manages water flow and prevents wastage. The system uses a **flow sensor, ultrasonic sensor, and microcontroller logic** to operate in two modes:
- 🟢 **Running Mode** (detects and limits daily water usage)
- 🔵 **Filling Mode** (monitors tank/container levels and prevents overflow)

---

## 🎯 Objectives

- Reduce water wastage in day-to-day activities  
- Enable real-time flow and level monitoring  
- Automate water control using sensors and logic  
- Promote sustainable domestic water usage

---

## 🛠️ Hardware Components

See the complete list in [`components_list`](components_list)

---

## ⚙️ Modes of Operation

### 🔄 Running Mode
- Uses **Flow Sensor (YF-S201)** to detect flow rate
- Automatically turns off pump/faucet after exceeding preset limit
- Leak detection and daily consumption tracking using EEPROM

### 📈 Filling Mode
- Uses **Ultrasonic Sensor** to measure water level in tank/container
- LCD shows real-time level data
- Alerts user with **buzzer** and **LED** when tank is full

---
## 🛠️ Code
 [`code.ino`](code.ino)
---
## 🧠 Technologies Used

- Arduino UNO (ATmega328)
- Hall-effect water flow sensor
- Ultrasonic sensor (HC-SR04)
- IR sensor (optional)
- Relay module for switching
- 16x2 LCD Display
- EEPROM data logging



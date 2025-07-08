# 🏠 ESP32 Home Automation System – KiCAD 9.0 Open Source Hardware Project

4-Channel Home Automation with ESP32 PCB This project is a 4-channel home automation system based on the ESP32, designed to control electrical appliances via Wi-Fi, MQTT, or a mobile app. The custom PCB integrates relays, optoisolated inputs, and an efficient power supply for reliable operation.

---

## 📄 Overview

This project is part of an open-source initiative to develop smart home hardware using the ESP32 and KiCAD 9.0. The board can be used for controlling lights, sensors, and other appliances over Wi-Fi or Bluetooth. The tutorial covers:

- Creating schematics with proper component symbols and wiring
- Designing a double-layer PCB using KiCAD
- Exporting production-ready Gerber files
- Assembling and soldering the board
- (Optional) Uploading firmware using PlatformIO or Arduino IDE

This project is suitable for makers, students, and electronics enthusiasts looking to learn PCB design and IoT development.

---

![Top View](relative/or/absolute/path/to/image.png)
![Bottom View](relative/or/absolute/path/to/image.png)
![Schematic](relative/or/absolute/path/to/image.png)

---

## 🔧 Features


✔ **ESP32-based Wi-Fi control** (supports web server & MQTT)  
✔ **4-Channel relay output** for appliance control  
✔ **Optoisolated inputs** for safe external switch connections  
✔ **Onboard buck converter** (AC/DC to 5V) for efficient power  
✔ **Compact PCB design** for easy enclosure integration  

---

## 1️⃣ Components Used

- **ESP32-WROOM-32** (Wi-Fi + Bluetooth MCU)  
- **4 x Relays** (5V or 12V, SPDT)  
- **Optocouplers** for switch inputs  
- **AC to DC Buck Converter** (e.g., HLK-PM03 or equivalent)  
- **Screw terminals** for easy wiring  
- **Status LEDs** for each relay & power indicator  

---

## 2️⃣ PCB Design Details

- Designed in **KiCad**  
- **2-layer PCB** for cost efficiency  
- Proper **relay isolation** from low-voltage ESP32 signals  
- **Wide power traces** for relay switching  

---

## 🔌 Applications

#### -Home lighting automation

#### -Remote appliance control

#### -Sensor integration (temperature, humidity, PIR)

#### -MQTT or Wi-Fi-based smart home nodes


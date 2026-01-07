# Raspberry Pi IoT Environment Monitoring System

## 📌 Project Overview
This project is an IoT-based environmental monitoring system built using Raspberry Pi and Node-RED.  
It monitors temperature, light conditions, motion, and gas leakage and displays real-time data on a dashboard.

---

## 🎯 Problem Statement
Manual monitoring of environmental conditions is inefficient and unreliable.  
This project provides an automated solution using sensors and IoT to monitor and visualize data in real time.

---

## 🎯 Aim
To design and implement a real-time environmental monitoring system using Raspberry Pi and Node-RED.

---

## 🧩 Components Used
- Raspberry Pi
- DHT22 – Temperature sensor
- PIR Motion Sensor
- MQ-2 Gas Sensor
- LDR (Light Sensor Module)
- LED with resistor
- Breadboard
- Jumper wires
- Power supply

---

## 🧠 Software & Tools
- Raspberry Pi OS
- Node-RED
- Node-RED Dashboard
- GPIO libraries

---

## 🔌 Hardware Connections
- DHT22 → GPIO 4  
- PIR Sensor → GPIO 17  
- MQ-2 (DO pin) → GPIO 27  
- LDR → GPIO 23  
- LED → GPIO 22  

All sensors share common GND and required power pins.

---

## 🔁 Working Principle
- DHT22 reads temperature values.
- PIR detects human motion.
- MQ-2 detects gas or smoke leakage.
- LDR detects light conditions.
- LED turns ON automatically in darkness.
- Node-RED processes sensor data.
- A dashboard displays temperature in real time.

---

## 📊 Dashboard Features
- Live temperature gauge
- Temperature history chart
- Automatic LED control using LDR

---

## ▶️ How to Run the Project
1. Install Raspberry Pi OS
2. Install Node-RED
3. Connect sensors as per wiring diagram
4. Import `flows.json` into Node-RED
5. Deploy the flow
6. Open the dashboard:

---

## 🎥 Demo Video
A short demo video showing the temperature gauge and chart is included in this repository.

---

## 📷 Screenshots
(Add dashboard and hardware images here)

---

## 📌 Results
- Temperature displayed correctly on dashboard
- Sensors worked reliably
- LED automation worked based on light condition

---

## 🏁 Conclusion
This project successfully demonstrates an IoT-based environmental monitoring system using Raspberry Pi and Node-RED.  
It helps in understanding real-time monitoring and hardware–software integration.

---

## 📚 What I Learned
- Raspberry Pi GPIO handling
- Sensor integration
- Node-RED flow design
- Dashboard creation
- IoT system implementation

---

## 👤 Author
**Fayaz Ahmed**

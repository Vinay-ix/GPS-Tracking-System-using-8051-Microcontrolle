# 📍 8051 GPS Tracker

A real-time GPS tracking system using the **AT89S52 (8051) microcontroller**. This project interfaces a GPS module with the microcontroller over UART, extracts real-time location coordinates, and displays them on a 16x2 LCD screen.

---

## 🧠 Objective

Design and implement a microcontroller-based GPS tracking system that:
- Reads NMEA data from a GPS NEO-6M module
- Parses and extracts latitude and longitude
- Displays location on a 16x2 LCD
- Demonstrates hardware interfacing and serial communication

---

## 📦 Features

- Real-time GPS coordinate tracking (Latitude & Longitude)
- UART serial communication (9600 baud, 8N1 format)
- LCD interfacing with 8051 (parallel communication)
- Simulation support using Proteus
- Assembly-level programming for 8051

---

## 🔧 Components Used

- **8051 Microcontroller (AT89S52)**
- **GPS NEO-6M Module**
- **16x2 LCD Display**
- Lithium-ion Battery
- Jumper Wires
- UART Serial Interface
- Proteus Software for Simulation

---

## 🧪 Simulation (Proteus)

- Simulated using **VGPS module** in Proteus
- Transmits sample NMEA GPGGA sentences
- Output displayed on LCD within the simulation

---

## 💻 Code Overview

- Initializes UART for 9600 baud communication
- Receives NMEA `$GPGGA` sentence
- Extracts Latitude and Longitude
- Displays values on LCD

---

## 🛠️ Applications

- Vehicle GPS Tracking
- Logistics and Fleet Monitoring
- Personal Navigation Devices
- Asset Tracking in Smart Cities

---

## 📂 Folder Contents

- `report/`: Full project documentation (DOCX)
- `hardware/`: Photos of the assembled hardware
- `simulation/`: Proteus circuit diagram (optional image)
- `gps_tracker.asm`: Assembly code used for 8051 (if available)

---

## 🎥 Demo

[📺 Watch on YouTube](https://www.youtube.com/watch?v=erZ1EfOQrkE)

---

## 🙋 Authors

- Vinay (22BEC1247)
- Mrinank Gaur (22BEC1258)
- Ralf Paul Victor (22BEC1222)
- Khushi Jain, Abhisha Chakrbarti, Abhishek, Manindra Gopireddy

Course: **BECE204L – Microprocessors and Microcontrollers**  
Faculty Guide: **Dr. S. Revathi**, VIT Chennai

---

## 📄 License

This project is for academic and educational purposes only.

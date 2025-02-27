

# 🔒 RFID Door Security System with Temperature Sensor

## 📄 Project Overview
This project implements a secure and efficient door locking system using RFID (RC522 module) and a temperature sensor (MLX90614). The system allows access only to authorized RFID tags and incorporates a temperature-based restriction, preventing access if a user’s temperature exceeds a predefined threshold.

## 📑 Contents
- **Report:** `RFID_Project_Report.pdf` (Detailed design, components, and analysis)
- **Code:** Arduino sketches for RFID authentication and temperature control
- **Schematics:** Circuit diagrams and wiring connections
- **Component List & Costs:** Breakdown of required hardware

## 🎯 Objectives
- Implement RFID-based door access control
- Store multiple RFID tags for authorized user access
- Integrate MLX90614 temperature sensor to restrict access if high temperature is detected
- Display user access status on an LCD screen
- Provide alerts using an active buzzer

## 🛠 Components & Hardware
- Arduino UNO R3
- RFID RC522 Module
- MLX90614 Infrared Temperature Sensor
- LCD Display with I2C module
- SG90 Servo Motor (for door lock mechanism)
- TCRT5000 IR Sensor
- Active Buzzer
- 1.5V Batteries & Jumper Wires

## 💰 Total Cost: ~3540 TK

## 📊 Features & Benefits
- **✔ Increased Security:** Unique RFID access for authorized users
- **✔ Contactless Operation:** No need for keys or manual passwords
- **✔ Temperature-Based Access Control:** Restricts entry if the user's temperature is elevated
- **✔ Real-Time Feedback:** LCD display shows access status and temperature readings

## ❌ Drawbacks & Limitations
- Higher cost compared to traditional locking systems
- Requires technical expertise for setup and maintenance
- Privacy concerns related to storing RFID and temperature data

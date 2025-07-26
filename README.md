# GUARDION-Saferide-Smart-Helmet-Project
# SAFERIDE HELMET SYSTEM 🪖

An IoT-based Smart Helmet system designed to enhance motorcycle rider safety by integrating critical safety technologies like alcohol detection, helmet detection, accident detection, and emergency communication using Arduino Mega.

---

 Overview

This smart helmet is developed as part of a summer project at **Madras Institute of Technology, Anna University**. It ensures that:

- The bike starts **only when the helmet is worn**
- It **detects alcohol consumption** and blocks the bike from starting
- It detects **accidents** using an accelerometer and sends **SMS alerts** with GPS location via GSM
- It uses **RF communication** between helmet and bike
- An **LCD display and relay** help control ignition and inform the rider

---

 Features

-  Helmet usage detection (limit switch)
-  Alcohol level sensing with MQ-3 sensor
-  Accident detection with MPU-6050 accelerometer
-  Real-time emergency SMS with GPS via SIM800L GSM module
-  Wireless RF communication between helmet and bike
-  Ignition control using relay (bike won’t start unless conditions are safe)
-  Visual feedback with LCD

## ▶ How to Use

1. Upload `transmitter.ino` to the Arduino Mega inside the helmet.
2. Upload `receiver.ino` to the Arduino Mega on the bike.
3. Connect and power all hardware components as per the circuit.
4. Test the system by:
   - Wearing the helmet (limit switch closes)
   - Blowing near the MQ-3 to simulate alcohol detection
   - Simulating accidents using movement (accelerometer triggers GSM alert)

---


---




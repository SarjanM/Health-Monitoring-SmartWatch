# Health Monitoring Smartwatch 🩺⌚

A low-cost, wearable IoT-based smartwatch designed to continuously monitor 
key physiological and motion parameters of the wearer in real time. Built 
using embedded sensors and microcontroller-based data acquisition, this 
project aims to provide accessible, real-time health tracking for personal 
wellness, elderly care, and remote patient monitoring.

## Features
- 🔴 **Heart Rate Monitoring** – Real-time pulse/BPM detection using a PPG-based sensor (e.g., MAX30100/MAX30102)
- 🫁 **Blood Oxygen (SpO2) Measurement** – Tracks blood oxygen saturation levels for early detection of respiratory issues
- 🌡️ **Body Temperature Sensing** – Continuous temperature monitoring using a digital temperature sensor
- 🏃 **Motion & Activity Tracking** – 3-axis acceleration data (via accelerometer/IMU such as MPU6050) to detect movement, steps, and posture/fall
- 📶 **Real-Time Data Transmission** – Sends sensor data via Bluetooth/Wi-Fi to a mobile app or cloud dashboard
- 📊 **Data Logging & Visualization** – Stores historical readings for trend analysis
- 🔋 **Low Power Design** – Optimized for extended battery life on a wearable device

## Hardware Components
- Microcontroller: ESP32 / Arduino Nano (specify yours)
- Heart Rate & SpO2 Sensor: MAX30100 / MAX30102
- Temperature Sensor: DS18B20 / DHT11 / MLX90614
- Accelerometer/Gyroscope: MPU6050 / ADXL345
- Display (optional): OLED/TFT screen
- Power: Li-Po battery + charging module

## Tech Stack
- Firmware: C/C++ (Arduino/ESP-IDF)
- Communication: Bluetooth Low Energy (BLE) / Wi-Fi
- Backend (if applicable): Node.js / Python / Firebase
- App/Dashboard: Flutter / React Native / Web dashboard

## Use Cases
- Personal fitness and wellness tracking
- Remote patient monitoring for elderly or chronically ill patients
- Early warning system for abnormal vitals (low SpO2, fever, irregular heart rate)
- Fall/activity detection using accelerometer data

## Getting Started
1. Clone the repository
2. Wire up the sensors as per the circuit diagram in `/docs`
3. Flash the firmware using Arduino IDE / PlatformIO
4. Pair with the companion app to view live readings

## Disclaimer
This project is intended for educational and personal wellness purposes only. 
It is **not a certified medical device** and should not be used for clinical 
diagnosis or treatment decisions.

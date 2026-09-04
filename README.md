# 🔥 Smart Firefighter Safety Vest

### Vegathon Embrix Hackathon

> An intelligent wearable safety system designed to improve firefighter safety and situational awareness.

## 🚨 Problem Statement
Firefighters work in hazardous environments with high temperature, poor air quality, limited visibility, and unpredictable conditions. During rescue operations, locating nearby people and maintaining situational awareness can be difficult.

## 💡 Proposed Solution
We developed a Smart Firefighter Safety Vest integrating mmWave radar, environmental sensors, Raspberry Pi, Arduino Mega, TFT display, audio alerts, and Bluetooth communication.

The system detects nearby humans, estimates the nearest person's distance, monitors environmental conditions, and provides immediate alerts.

## ✨ Key Features
- Human detection and counting
- Nearest human distance measurement
- Temperature warning
- Air-quality warning
- Voice alerts
- TFT display
- HC-05 Bluetooth communication
- Wearable safety design

## 🏗️ System Architecture
```text
IWR6843AOP Radar
        ↓
   Raspberry Pi
        ↓
    Arduino Mega
     ↙    ↓    ↘
   TFT   Audio   HC-05
                  ↓
               Android
```

## 🔧 Hardware
- IWR6843AOP mmWave Radar
- Raspberry Pi
- Arduino Mega
- TFT Display
- HC-05 Bluetooth Module
- MP3 Player + Speaker
- Temperature Sensor
- Air Quality Sensor

## 💻 Technologies
Python • Arduino C/C++ • Raspberry Pi • Arduino Mega • mmWave Radar • UART • Bluetooth

## 🔄 Working
1. Radar detects humans.
2. Raspberry Pi processes radar data.
3. Human count and nearest distance are calculated.
4. Arduino receives the processed information.
5. TFT displays the status.
6. Audio provides voice alerts.
7. HC-05 sends selected information to Android.

## 📡 Example Output
```text
HUMANS   : 2
NEAREST  : 1.85 m
STATUS   : HUMAN DETECTED
```

## 🚀 Innovation
The project combines human detection, distance monitoring, environmental monitoring, voice assistance, visual feedback, and wireless communication into a single wearable firefighter safety platform.

## 🔮 Future Scope
GPS tracking • Fall detection • Heart-rate monitoring • Automatic SOS • Thermal camera • AI-based hazard detection • Long-range communication

## 🏆 Hackathon
**Event:** Vegathon Embrix  
**Project:** Smart Firefighter Safety Vest  
**Domain:** Embedded Systems • IoT • Wearable Safety

> ⚠️ Prototype for educational, research, and hackathon purposes.

# Iot-Flood-Monitoring-System
Iot based smart flood monitoring using Esp32 and sensors
# IoT-Based Flood Monitoring System

**Author:** Tanishka Yadav
**Project type:** Embedded IoT / Flood monitoring

## Overview
A low-cost IoT system to monitor water level and environmental parameters (rain, temperature, humidity) in real time using ESP32. The device triggers local buzzer alerts and sends remote notifications via an IoT dashboard.

## Problem Statement
Floods cause significant damage due to delayed or no early warnings in vulnerable areas. Many existing solutions are either costly or not easily deployable in rural locations.

## Proposed Solution
A compact, battery/solar compatible ESP32-based unit with:
- Ultrasonic sensor for water level
- Rain sensor for rainfall intensity
- DHT11 for temperature & humidity
- Buzzer for local alerts
- IoT integration (Blynk / MQTT) for remote monitoring & notifications

## Features
- Real-time water-level monitoring
- Threshold-based buzzer & remote alerts
- On-device LCD/OLED for local readings
- Cloud dashboard for remote monitoring
- Simple hardware — easy to replicate

## Hardware
- ESP32 Dev Module  
- HC-SR04 ultrasonic sensor (or similar)  
- Rain intensity sensor  
- DHT11 (or DHT22)  
- Buzzer  
- LCD/OLED display  
- Power supply (power bank/solar + battery)

## Firmware
Firmware available in `/firmware`. To upload using Arduino IDE:
1. Open `flood_monitor.ino` in Arduino IDE.
2. Select **Tools → Board → ESP32 Dev Module**.
3. Install libraries listed in `/firmware/libraries.txt`.
4. Insert your WiFi credentials and Blynk/MQTT auth token into the config section.
5. Upload to the device.

## Schematics & Photos
See ![connections (flood monitoring)](https://github.com/user-attachments/assets/8a431026-d638-425f-bad9-7d8babec22d7)
for circuit diagram and photos of the prototype.

## Demo
A video demo is available in 

https://github.com/user-attachments/assets/38b2e235-1d94-4f96-9a99-56965b1a8559

## Certificate

Certificate from the event is in `[prastuti 2 0 certificate](https://github.com/user-attachments/assets/c6fb0fa7-6e40-4703-9646-2d6388eee973)

## Future Work
- GPS-tagged alerts for geographically-aware notifications  
- Battery/solar optimization for long-term remote deployment  
- Cloud analytics & basic flood prediction  

Your Name — tanishkayadav2212@gmail.com 
GitHub: https://github.com/<twoleggg>

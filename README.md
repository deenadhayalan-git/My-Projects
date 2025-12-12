# MEMS-Based Machine Vibration Monitoring and Management System

**Role:** Team Member — Hardware & Implementation  
**Tools:** ESP32, ADXL345, GSM (SIM800), Blynk, Arduino IDE, 16x2 LCD  
**Description:** Portable IoT system that measures 3-axis vibration, shows readings on LCD and Blynk, and sends SMS alerts when thresholds are exceeded. Designed for low-cost predictive maintenance.

## Features
- Real-time 3-axis vibration monitoring (ADXL345)
- Local display (16x2 LCD) + remote visualization (Blynk)
- SMS alert via GSM when vibration > threshold
- Portable power supply (Li-ion battery + charge module)

## How to run
1. Flash `code/vibration_monitor.ino` to ESP32 using Arduino IDE.  
2. Connect ADXL345 to SDA/SCL, GSM to TX/RX, LCD to digital pins.  
3. Configure Wi-Fi and Blynk credentials in the sketch.

## Contact
Deenadhayalan — deena20061234@gmail.com

# 🌡️ Arduino Digital Thermometer

## 📌 Overview
This project creates a **digital thermometer** using Arduino, a DS18B20 temperature sensor, and an LCD display.  
It shows the live temperature in Celsius on the display + serial monitor.

---

## 🛠️ Hardware Required
- Arduino Uno/Nano  
- DS18B20 Temperature Sensor  
- 4.7kΩ Resistor (pull-up for data line)  
- LCD Display (16x2, I2C module recommended)  
- Jumper wires, breadboard  

---

## 🔌 Wiring
- **DS18B20 Sensor**  
  - VCC → 5V  
  - GND → GND  
  - Data → D2 (with 4.7kΩ resistor between Data & VCC)  

- **LCD (I2C)**  
  - VCC → 5V  
  - GND → GND  
  - SDA → A4  
  - SCL → A5  

---

## ▶️ Usage
1. Install **OneWire** and **DallasTemperature** libraries from Arduino IDE Library Manager.  
2. Install **LiquidCrystal_I2C** library.  
3. Upload the code to Arduino.  
4. View real-time temperature on LCD and Serial Monitor.  

---

## 📂 Repo Structure

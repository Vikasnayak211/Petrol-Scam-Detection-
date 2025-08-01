# ⛽ Petrol Scam and Adulteration Detection System

A low-cost embedded system designed to detect **fuel adulteration** and prevent **petrol scams**. It helps identify mixing of **kerosene or ethanol** in petrol and measures the **flow volume** accurately using sensors.

---

## 🛠️ Features

- Detects **ethanol or kerosene** mixing using **MQ-2 and MQ-3 gas sensors**
- Measures and displays **volume of petrol** delivered using a **flow sensor**
- Results are shown in **real-time** on an **LCD screen**
- Helps prevent fuel fraud at petrol stations and during transport

---

## 🔧 Components Used

- Arduino Uno
- MQ-2 Gas Sensor (for kerosene detection)
- MQ-3 Gas Sensor (for ethanol detection)
- Flow Sensor (for volume measurement)
- 16x2 LCD Display
- I2C Module (to simplify LCD connections)
- Wires, Breadboard, Power Supply

---

## 📂 Code Files

- `fuel_detector.ino` – Arduino code to read sensors and display output

---

## 📊 Output Information

- LCD shows whether petrol is **pure** or **adulterated**
- Displays the **amount of petrol** passed through the pipe
- If any abnormal gas value is detected → alerts user to possible **fuel mixing**

---

## 🧠 How It Works

1. Petrol vapor is passed through a sealed chamber containing **MQ sensors**
2. Sensors detect specific gas concentrations (ethanol, kerosene)
3. A flow sensor measures how much petrol flows during delivery
4. Based on sensor values, LCD shows:
   - “Pure Petrol” ✅
   - “Adulterated with Kerosene” ⚠️
   - “Ethanol Detected” ⚠️
5. Optional: Add buzzer/light alert when fraud is detected

---

## 🌟 Future Scope

- Add **GSM module** to send alerts to mobile or central authority
- Add **SD card module** to log fuel transactions and readings
- Add **Bluetooth or IoT** support to push data to a mobile app
- Improve calibration to detect exact percentage of mixing

---

## 👨‍🔧 Developed By

**Vikas Nayak**  
2nd Year Mechanical Engineering  
GitHub: [https://github.com/Vikasnayak211](https://github.com/Vikasnayak211)

---

> 🔒 This project promotes transparency in fuel supply and protects consumers from petrol fraud.

# Iot_Project
A wireless LCD display system using Bluetooth that receives and displays text data transmitted from a nearby host device (like a smartphone or computer).
# 📡 Wireless Notice Board Using Bluetooth (IoT)

## 📌 Project Description
The **Wireless Notice Board Using Bluetooth** is an IoT-based embedded system that allows notices to be displayed wirelessly using a mobile phone. Messages are sent via Bluetooth and displayed on a **16×2 LCD** connected to an **Arduino Uno**.  
This system replaces traditional manual notice boards and enables quick, wireless message updates.

---

## 🎯 Project Objectives
- To design a Bluetooth-based wireless notice board
- To transmit text messages wirelessly using a mobile device
- To display messages on an LCD using Arduino Uno
- To implement serial communication using Embedded C

---

## 🧩 Components Required

- Arduino UNO  
- Bluetooth Module **HC-05**  
- **16×2 LCD Display**  
- Jumper Wires  
- **1K Ω Resistor**  
- Half Breadboard  
- USB Cable (for programming and power supply)

---

## 💻 Software Used
- Arduino IDE  
- Embedded C  
- Bluetooth Controller Mobile Application  
- Windows Operating System  

---

## 🔗 System Block Diagram (Explanation)
1. Mobile phone sends message via Bluetooth  
2. HC-05 Bluetooth module receives data  
3. Arduino Uno processes the incoming data  
4. Message is displayed on the 16×2 LCD  

---

## ⚙️ Working Principle
- The HC-05 Bluetooth module is interfaced with the Arduino using serial communication.
- Text messages are sent from a mobile phone using a Bluetooth app.
- Arduino continuously listens to incoming serial data.
- When data is received, it is displayed on the LCD.
- Messages can be changed anytime wirelessly without physical access to the board.

---

## 🔌 Circuit Connections (Overview)
| Component | Arduino Pin |
|---------|-------------|
| HC-05 TX | RX (Pin 0) |
| HC-05 RX | TX (Pin 1) via 1K Ω resistor |
| LCD RS | Digital Pin |
| LCD EN | Digital Pin |
| LCD D4–D7 | Digital Pins |
| LCD VCC | 5V |
| LCD GND | GND |

*(Pin numbers may vary depending on code configuration)*

---

## 📂 Project Structure

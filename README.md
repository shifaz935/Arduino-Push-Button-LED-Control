# 🔘 Arduino Push Button LED Control

An interactive Arduino project built using Tinkercad that demonstrates how a push button can control an LED. This project introduces the concept of digital input and output, forming the foundation of interactive embedded systems and IoT applications.
## 📌 Project Overview

This project allows an Arduino Uno to read the state of a push button and control an LED based on user interaction.
### Working Principle

```
Press Button
      │
      ▼
Arduino Reads Input
      │
      ▼
LED Turns ON

Release Button
      │
      ▼
Arduino Reads Input
      │
      ▼
LED Turns OFF
```

This demonstrates the **Input → Process → Output** cycle used in almost every embedded and IoT system.

## 🎯 Features

- Interactive LED control using a push button
- Reads digital input from a button
- Controls digital output to an LED
- Demonstrates conditional programming using decision-making logic
- Beginner-friendly Arduino project

## 🛠 Components Used

- Arduino Uno R3
- Breadboard
- Push Button
- Red LED
- 220Ω Resistor
- Jumper Wires

## 🔌 Circuit Connections

| Component | Arduino Pin |
|----------|-------------|
| Push Button | Digital Pin 2 |
| LED | Digital Pin 13 |
| LED Cathode | GND (through 220Ω resistor) |

## 💡 Learning Outcomes

Through this project, I learned:

- Difference between digital input and digital output
- Reading button input using Arduino
- Controlling an LED based on user input
- Understanding interactive embedded systems
- Using conditional logic in Arduino programs
- Building simple user-controlled electronic circuits

## 🌍 Real-World Applications

The same concept is used in:

- Smart Doorbells
- Home Automation Systems
- Elevator Buttons
- Security Systems
- Industrial Control Panels
- IoT Devices
- Smart Switches
- Access Control Systems

## ▶️ Simulation

This project was designed and tested using **Tinkercad Circuits**.



## 📁 Project Structure

```
Arduino-Push-Button-LED-Control/
│── Push_Button_LED.ino
└── README.md
```

## 🚀 Future Improvements

- Toggle LED state with a single button press
- Control multiple LEDs using one button
- Add a buzzer for audio feedback
- Integrate an LCD to display button status
- Connect to ESP32/ESP8266 for IoT-based remote monitoring
- Implement software debouncing for reliable button detection




## 👨‍💻 Author

**Shifas P S**


- GitHub: https://github.com/shifaz935
- LinkedIn: https://www.linkedin.com/in/shifas-p-s-965895397

---


⭐ If you found this project useful, feel free to star this repository and explore my other Arduino and IoT projects.

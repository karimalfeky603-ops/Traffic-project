# 🚦 Smart Traffic Light System (Arduino Project)

A smart **traffic light control system** built with **Arduino**, **LEDs**, and a **Servo motor** to simulate the movement of vehicles and automatic traffic control.  
This project demonstrates how microcontrollers can manage road signals and barriers in a realistic way.

---

## 🧠 Project Idea

The system automatically controls traffic lights (Red, Yellow, Green) and uses a **servo motor** to simulate a gate or barrier that opens and closes depending on the light status.  
It can be used as a small-scale model for **smart city traffic management**.

---

## ⚙️ Components Used

| Component | Quantity | Description |
|------------|-----------|-------------|
| Arduino UNO | 1 | Main controller |
| Red LED | 1 | Stop signal |
| Yellow LED | 1 | Warning signal |
| Green LED | 1 | Go signal |
| Servo Motor (SG90) | 1 | Simulates the barrier arm |
| Jumper wires | — | Connections |
| Breadboard | 1 | Circuit assembly base |
| Resistors (220Ω) | 3 | To limit current for LEDs |

---

## 🔌 Circuit Diagram (Concept)
Green LED → Pin 2
Yellow LED → Pin 3
Red LED → Pin 4
Servo Motor → Pin 9
GND → Common groun



*(You can include a Fritzing diagram image here for a more visual presentation.)*

---

## 💻 Code Overview

- Controls 3 LEDs representing traffic light sequence.  
- Servo barrier lifts when light is green and closes when red.  
- Adjustable timing for each light phase.  
- Simple logic written in Arduino C++.

---

## 🧩 Features

✅ Simulates real traffic light sequence  
✅ Integrates servo-controlled barrier  
✅ Easy to modify and expand  
✅ Great educational project for Arduino beginners

---

## ▶️ How to Run

1. Connect all components as shown in the circuit diagram.  
2. Upload the code to your Arduino UNO using the Arduino IDE.  
3. Power up the board and observe the light cycle and servo movement.

---

## 🚀 Future Improvements

- Add an **ultrasonic sensor** to detect vehicles and optimize light timing.  
- Display traffic status on an **LCD screen**.  
- Add **buzzer alerts** or **Wi-Fi control** via ESP8266 module.

---

## 👤 Author

**Kareem Alfeky**  
Arduino Developer | Student | Tech Enthusiast  
📍 Egypt  
🔗 [GitHub Profile](https://github.com/karimalfeky603-ops)

---

## 🪪 License

This project is licensed under the **MIT License** — free to use, modify, and share.

---




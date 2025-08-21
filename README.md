# 📘 LED Control with Push Buttons – Arduino Uno

## 🧠 Idea  
This project demonstrates how to control three LEDs using three push buttons with an Arduino Uno. Each button toggles a specific LED on or off. It’s a beginner-friendly project that teaches the basics of digital input/output and how to use push buttons to interact with microcontrollers.

---

## ⚙️ Components Used  
- Arduino Uno board  
- 3 LEDs (any color)  
- 3 Push buttons  
- 6 Resistors (3 × 220Ω for LEDs, 3 × 10kΩ for buttons)  
- Breadboard  
- Jumper wires  
- USB cable for programming

---

## 🔌 Circuit Connections

| Component  | Arduino Pin | Notes                         |
|------------|-------------|-------------------------------|
| LED 1      | Pin 2       | Connect through 220Ω resistor |
| LED 2      | Pin 3       | Connect through 220Ω resistor |
| LED 3      | Pin 4       | Connect through 220Ω resistor |
| Button 1   | Pin 5       | Use pull-down resistor (10kΩ) |
| Button 2   | Pin 6       | Use pull-down resistor (10kΩ) |
| Button 3   | Pin 7       | Use pull-down resistor (10kΩ) |

Each button should be connected between the digital pin and ground, with a pull-down resistor to ensure stable input.

---

## 🧪 How It Works  
- When Button 1 is pressed, LED 1 toggles its state (ON/OFF).  
- When Button 2 is pressed, LED 2 toggles its state.  
- When Button 3 is pressed, LED 3 toggles its state.  
- The Arduino reads the button state and changes the LED accordingly.





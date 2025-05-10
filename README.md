# Automatic Gate Demo Kit 🚪🔊🔵🔴

This project simulates an **Automatic Gate System** using an **Arduino Uno**, demonstrating how sensor input can control actuators and indicators like a **servo motor**, **LEDs**, and a **buzzer**.

## 🔍 Project Description

The **Automatic Gate Demo Kit** mimics the behavior of a real-world smart gate, which:

* Uses an **Ultrasonic Sensor (HC-SR04)** to detect nearby objects (e.g., vehicles or people).
* Opens the gate by rotating a **servo motor to 90°** when an object is detected within a predefined threshold distance.
* Keeps the gate open for **5 seconds**, then closes it (rotates the servo back to 0°).
* Lights a **Blue LED** while the gate is open and a **Red LED** when the gate is closed.
* Activates a **buzzer** to beep **continuously while the gate is open**, signaling active passage.

## 💪 Hardware Components

* Arduino Uno
* Ultrasonic Sensor (HC-SR04)
* Servo Motor (e.g., SG90)
* A car to test this


## 🧠 Code Features

* Distance reading from the ultrasonic sensor.
* Conditional logic to determine when to open/close the gate.
* Time delay to keep the gate open.
* LED and buzzer indicators based on the gate's state.

## 📁 Files

* `demokit.ino`: The main Arduino sketch containing the control logic.
* `README.md`: You're reading it 💅🍻 — an overview of the project setup and features.

## 🚀 How to Use

1. Connect the components to the Arduino as per the circuit diagram.
2. Upload the `demokit.ino` code to your Arduino Uno using the Arduino IDE.
3. Power up your Arduino and watch your gate smartly swing into action!

---

Made with love by **ISHEMA NKERABAHIZI Love** 💖✨

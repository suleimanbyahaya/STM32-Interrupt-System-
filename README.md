# STM32 Interrupt-Driven Event Detection System

This project demonstrates the design and implementation of an interrupt-driven event detection system using an STM32F4 microcontroller and HAL library.

## 📌 Project Overview

The system uses a push button as an input device and an LED as an output indicator. Instead of continuously checking the button state (polling), the system uses an external interrupt (EXTI) to detect button presses in real time.

When the button is pressed, an interrupt is triggered and the LED toggles instantly.

---

## ⚙️ Features

- GPIO input and output configuration
- External interrupt (EXTI) setup
- Real-time event detection
- Comparison between polling and interrupt methods

---

## 🧰 Hardware Used

- STM32F4 Development Board
- Push Button (PC13)
- LED (PA5)
- 220Ω Resistor

---

## 🔌 Circuit Description

- LED connected to **PA5**
- Push button connected to **PC13**
- Button press generates a **falling edge interrupt**

---

## 💻 Software Used

- STM32CubeIDE
- HAL (Hardware Abstraction Layer)

---

## 📁 Project Structure

# Automatic Street Light Controller

An Arduino-based automatic street light controller that turns a light ON in darkness and OFF during daylight using an LDR (Light Dependent Resistor).

---

## 📌 Project Overview

This project demonstrates a basic real-world automation system similar to street lighting used in cities.  
The system senses ambient light intensity using an LDR and controls a light accordingly, helping reduce unnecessary power consumption.

The project was implemented by following a reference design and independently assembling, testing, and validating the circuit and code.

---

## 🎯 Objective

- To understand sensor interfacing with Arduino
- To implement conditional logic based on sensor input
- To simulate an energy-efficient street lighting system

---

## 🔧 Components Used

- Arduino UNO  
- LDR (Light Dependent Resistor)  
- LED (represents street light)  
- Resistors  
- Breadboard  
- Jumper wires  

---

## ⚙️ Working Principle

1. The LDR measures ambient light intensity.
2. Arduino reads the analog value from the LDR.
3. If the light level falls below a predefined threshold:
   - LED turns **ON**
4. If sufficient light is detected:
   - LED turns **OFF**

This logic mimics automatic street light operation.

---

## 🧠 Logic Flow



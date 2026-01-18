# IoT Plant Watering System with NodeMCU ESP8266 and Blynk

An automated plant watering system that monitors soil moisture and waters the plant automatically using a NodeMCU ESP8266 microcontroller and the Blynk IoT platform.

This system reads soil moisture levels from a sensor and controls a water pump through a relay. You can also monitor and control the system remotely using the Blynk app. :contentReference[oaicite:0]{index=0}

---

## 📌 Project Overview

This IoT project automates plant watering by connecting a soil moisture sensor and a water pump to a NodeMCU ESP8266 board over Wi-Fi. The system continuously reads moisture values and activates the pump when moisture falls below a predefined threshold. A Blynk dashboard allows remote monitoring and control from a smartphone or computer. :contentReference[oaicite:1]{index=1}

---

## 🎯 Objective

- Build a real-world IoT system for plant care  
- Interface sensors and actuators with NodeMCU  
- Enable remote interaction via the Blynk app
- Save water by intelligent watering only when needed

---

## 🔧 Components Used

- NodeMCU ESP8266 board :contentReference[oaicite:2]{index=2}  
- Soil moisture sensor :contentReference[oaicite:3]{index=3}  
- Relay module :contentReference[oaicite:4]{index=4}  
- Mini water pump (12 V DC) :contentReference[oaicite:5]{index=5}  
- Water tubing :contentReference[oaicite:6]{index=6}  
- Power supply (e.g., 5 V for NodeMCU, 12 V for pump) :contentReference[oaicite:7]{index=7}  
- (Optional) LCD display with I2C :contentReference[oaicite:8]{index=8}  
- Jumper wires and breadboard :contentReference[oaicite:9]{index=9}  

---

## ⚙️ How It Works

1. The soil moisture sensor continually measures moisture level in the soil.
2. NodeMCU reads sensor values using its analog input.
3. If moisture falls below a set threshold, NodeMCU activates the relay to run the water pump.
4. Moisture data and control status are sent to the Blynk app dashboard in real time. :contentReference[oaicite:10]{index=10}

---

## 🗂 Project Structure

Plant_Watering_System/
├── README.md
├── code/
│ └── plant_watering_esp8266.ino
├── hardware/
  └── circuit_diagram.jpg


---

## 📱 Blynk App Setup

1. Create a new project on the Blynk web dashboard or mobile app.
2. Choose **NodeMCU** as the device and set the connection type to Wi-Fi.
3. Add widgets such as a gauge (to display moisture) and a button (to control the pump).
4. Copy the auth token provided by Blynk and paste it into your code. :contentReference[oaicite:11]{index=11}

---

## ▶ How to Upload and Run

1. Connect NodeMCU to your computer via USB.
2. Open the `.ino` file in Arduino IDE.
3. Install the required libraries (Blynk, WiFi, etc.).
4. Insert your Blynk auth token, Wi-Fi SSID, and password in the code.
5. Select the correct board and port, then upload.
6. Once uploaded, monitor and control the system from the Blynk dashboard. :contentReference[oaicite:12]{index=12}

---

## 📊 Visuals

Add photos and diagrams to show your build — they make the project more credible and easier to understand.

---

## 🧠 What I Learned

- Interfacing NodeMCU with sensors and actuators  
- Setting up real-time IoT communication using the Blynk platform  
- Designing logic to automate hardware based on sensor values  
- Troubleshooting Wi-Fi and hardware integration

---

## 🔮 Future Enhancements

- Add multiple moisture sensors across plant beds  
- Integrate weather forecast data to avoid watering during rain  
- Add a manual override switch on the Blynk interface  
- Log moisture data to a cloud database for analytics

---

## 👤 Author

Suyash


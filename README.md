## Envi-Rover

![Envi-Rover Screenshot](Images/rover_main_2.jpg)

## Description:
The **Envi-Rover** is a LoRa-based, long-range, remotely operated robotic system designed to monitor environmental parameters and detect obstacles in hazardous or inaccessible areas. The rover is controlled using `W`, `A`, `S`, `D` keys for movement and `X` to stop. Data from the rover is continuously received at the controller, allowing for real-time monitoring and control remotely without any hastle.

It integrates [ESP32](https://www.espressif.com/en/products/socs/esp32) with various sensors (temperature, humidity, illumination, and gas detection) and a LoRa communication module to transmit data over long distances. Users can access the data via [Blynk](https://blynk.io/) on mobile or PC.

🎥 **Rover :**  
<p align="left">
  <img src="Images/ani.gif" alt="Envi-Rover Demo" width="300"/>
</p>

---

## How it Works:

- The rover continuously collects data from sensors and transmits it via LoRa to the controller.  
- Users can send movement commands (`W`, `A`, `S`, `D`) to the rover, and `X` stops it.  
- Ultrasonic sensor with servo rotates automatically to detect obstacles and avoid collisions.  
- Blynk integration allows users to view real-time data on mobile or PC dashboards.  
- Data can be accessed anytime, enabling remote monitoring even in inaccessible locations.

---

## Features:

- **Remote Control:** Move the rover using `W`, `A`, `S`, `D` keys; `X` to stop.  
- **Real-Time Data Monitoring:** Temperature, humidity, gas levels, and illumination are continuously monitored and transmitted.  
- **Long-Range Communication:** LoRa module enables data transmission over large distances.  
- **Obstacle Detection:** Ultrasonic sensor with servo rotation detects and avoids obstacles automatically.  
- **Blynk Integration:** View live environmental data from anywhere using the **Blynk dashboard**.  
- **Deployment Ready:** Suitable for agriculture, disaster zones, industrial environments, and scientific research.

---

## 🧭 System Flowchart

Below is the system flow for **data transmission and control** between the **Rover** and **Controller**.
  
<p align="center">
  <img src="Images/flow_chart.png" alt="Envi-Rover Flowchart" width="700"/>
</p>

---

## 📷 Images & Visuals

A collection of Images showcasing the **Envi-Rover**, **Blynk Dashboard**, and **System Components**.

### 🚘 Rover Setup
<p align="center">
  <img src="Images/rover_2.png" alt="Rover Setup" width="550"/>
</p>
<p align="center"><em>The complete Envi-Rover unit with sensors, LoRa module, and power system.</em></p>

---

### 🌐 Blynk Dashboard (Web)
<p align="center">
  <img src="Images/blynk_desktop.jpg" alt="Blynk Web Dashboard" width="600"/>
</p>
<p align="center"><em>Blynk web dashboard showing real-time sensor data visualization.</em></p>

---

### 📱 Blynk Dashboard (Mobile)
<p align="center">
  <img src="Images/blynk_mobile1.jpg" alt="Blynk Mobile 1" width="200"/>
  &nbsp;&nbsp;&nbsp;
  <img src="Images/blynk_mobile2.jpg" alt="Blynk Mobile 2" width="200"/>
</p>
<p align="center"><em>Blynk mobile app screenshots displaying live readings.</em></p>

---

### 📊 Sensor Readings
<p align="center">
  <img src="Images/readings.png" alt="Blynk Readings" width="700"/>
</p>
<p align="center"><em>Example of temperature, humidity, and gas concentration readings from the rover.</em></p>

---

### ⚙️ Arduino Setup
<p align="center">
  <img src="Images/arduino.png" alt="Arduino Wiring 1" width="700"/>
</p>
<p align="center"><em>Arduino IDE programming and hardware setup with ESP32 and LoRa modules.</em></p>

---

## Use Cases:

- **Agriculture:** Real-time environmental monitoring and surveys.  
- **Disaster Management:** Monitoring air quality, temperature, and obstacles in dangerous areas.  
- **Industrial Environments:** Detecting unsafe conditions or gas leaks remotely.  
- **Smart Cities:** Integration into city-wide environmental monitoring networks.  
- **Scientific Research:** Collecting field data in remote or difficult terrains.

---

## Technology Stack:

### Hardware:
- ESP32 Microcontroller  
- LoRa (SX1278) Transceiver Module  
- Sensors:
  - DHT22 (Temperature & Humidity)
  - MQ135 (Gas)
  - LDR (Light Detection)
- Power Supply / Battery Unit

### Software:
- Arduino IDE  
- ESP32 board & LoRa modules (TX/RX)  
- Sensor Libraries (DHT22, MQ135, LDR)  
- Blynk for real-time data visualization  
- System & display code for rover control

---

## Links:

- [ESP32](https://www.espressif.com/en/products/socs/esp32)  
- [LoRa SX1278](https://www.semtech.com/products/wireless-rf/lora-transceivers)  
- [Blynk](https://blynk.io/)

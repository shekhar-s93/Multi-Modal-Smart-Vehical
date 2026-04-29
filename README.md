# Multi-Modal Smart Car

![ESP32](https://img.shields.io/badge/ESP32-IoT-blue)
![Arduino](https://img.shields.io/badge/Arduino-C++-green)
![Status](https://img.shields.io/badge/Project-Working-success)

---

## Project Description

The **Multi-Modal Smart Car** is a WiFi-controlled smart vehicle built using an ESP32 microcontroller.

The car can be controlled through a web-based interface and supports multiple intelligent driving modes, including:

- Manual Control
- Obstacle Avoidance Mode
- Follow Mode

It also includes useful features such as speed control, headlights, indicators, hazard lights, brake lights, and LCD display support.

---

## Features

-  ESP32 WiFi Access Point
-  Web-based remote control
-  Manual driving controls
-  Obstacle Avoidance Mode
-  Follow Mode using ultrasonic sensor
-  Speed control using PWM
-  Headlight control
-  Left and right indicators
-  Hazard light mode
-  Brake light system
-  16x2 I2C LCD display
-  Keyboard control support

---

## Technologies Used

- ESP32
- Arduino Framework
- C++
- HTML
- CSS
- JavaScript

---

## Software Required

| Software | Function |
|---|---|
| Arduino IDE | For Upload the Code in ESP32 |
| Web Browser (Chrome, M.S Edge, Brave) | For Controll the Car | 

## Hardware Components

| Component | Description |
|---|---|
| ESP32 Board | Main microcontroller |
| L298N Motor Driver | Controls DC motors |
| 4 DC Motors | Used for car movement |
| HC-SR04 Ultrasonic Sensor | Used for obstacle detection and follow mode |
| 16x2 I2C LCD | Displays mode, speed, and distance |
| 2 White LEDs | Headlights |
| 2 Red LEDs | Brake lights |
| 4 Yellow LEDs | Both Side Indicator (LEFT or RIGHT) |
| Ignition Swithch | Turn ON the car using key |
| 3s Lithium - ions Battery | Power the entire car |
| 3s BMS | Protect Battery from Overcharging and Discharging |
| BUCK Converter | Give eject power to ESP as it required (5 volts) |
| Charging Level Indicatior | To use how much battery is charged |
| Push Button | To turn on the Charging level Indicator |

---

## Pin Configuration

| Component | ESP32 Pin |
|---|---|
| Ultrasonic TRIG | GPIO 18 |
| Ultrasonic ECHO | GPIO 19 |
| LCD | I2C Pins |
| Motors | Connected through L298N Motor Driver |
| LEDs | Connected to assigned GPIO pins |

---

## 📂 Project Resources

| Resource | Link |
|--------|------|
| 📘 Blackbook | [View](./BLACKBOOK) |
| 🔌 Circuit Diagram | [View](./DIAGRAM) |
| 💻 Source Code | [Open](./Source_Code) |
| 📸 Images | [View](./images/) |


## WiFi Details

The ESP32 creates its own WiFi network.

```text
SSID: Multi_Modal_Smart_Vehical
Password: 0707070707
```

---

## 👨‍💻 Author

**Shekhar Suman**

## 🎓 Education

**BACHELOR of SCIENCE IN INFORMATION TECHNOLOGY**

---
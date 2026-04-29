# ESP32 Multi-Modal Smart Car

![ESP32](https://img.shields.io/badge/ESP32-IoT-blue)
![Arduino](https://img.shields.io/badge/Arduino-C++-green)
![Status](https://img.shields.io/badge/Project-Working-success)

---

## Project Description

The **ESP32 Multi-Modal Smart Car** is a WiFi-controlled smart vehicle built using an ESP32 microcontroller.

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
- L298N Motor Driver
- HC-SR04 Ultrasonic Sensor
- I2C LCD Display

---

## Hardware Components

| Component | Description |
|---|---|
| ESP32 Board | Main microcontroller |
| L298N Motor Driver | Controls DC motors |
| DC Motors | Used for car movement |
| HC-SR04 Ultrasonic Sensor | Used for obstacle detection and follow mode |
| 16x2 I2C LCD | Displays mode, speed, and distance |
| LEDs | Headlights, indicators, hazard, and brake lights |

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

## WiFi Details

The ESP32 creates its own WiFi network.

```text
SSID: Multi_Modal_Smart_Vehical
Password: 0707070707

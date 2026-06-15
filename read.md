# 🤖 NEXUS – Autonomous Service Robot

An intelligent WiFi-enabled mobile robot designed to demonstrate autonomous navigation, obstacle avoidance, and real-time embedded control on resource-constrained hardware.

Built around the ESP8266 NodeMCU, NEXUS combines wireless communication, sensor-based decision making, differential drive control, and a browser-based control interface into a single autonomous robotic platform.

---

## 📷 Project Gallery

### Robot Platform

![NEXUS Robot](images/robot.jpg)

### Web Control Dashboard

![Control Panel](images/control-panel.jpg)

### Autonomous Navigation Demo

![Navigation](images/navigation.jpg)

---

## ✨ Highlights

* 🌐 Browser-based robot control (No mobile app required)
* 🚗 Manual, Autonomous & Smart Navigation modes
* 📡 ESP8266-hosted WiFi control panel
* 🚧 Real-time obstacle detection and avoidance
* ⚡ Non-blocking firmware architecture using `millis()`
* 📺 OLED status display with live robot feedback
* 🛑 Emergency stop and safety lock mechanism
* 🔋 Fully portable battery-powered platform

---

## 🧠 System Architecture

NEXUS hosts its own WiFi network and web interface, allowing any device on the network to control the robot directly through a browser.

The robot continuously:

* Reads ultrasonic sensor data
* Processes navigation decisions
* Updates the OLED display
* Handles web requests
* Controls motor movement

all simultaneously without blocking execution.

---

## 🔧 Hardware Stack

| Component         | Purpose              |
| ----------------- | -------------------- |
| ESP8266 NodeMCU   | Main Controller      |
| HC-SR04           | Distance Measurement |
| L298N Driver      | Motor Control        |
| N20 Geared Motors | Differential Drive   |
| SSD1306 OLED      | Status Display       |
| 7.4V LiPo Battery | Power Supply         |

---

## 🚀 Navigation Modes

### 🎮 Manual Mode

Direct browser-based control using movement commands.

### 🤖 Autonomous Mode

Fully autonomous movement with obstacle detection and route correction.

### 🧠 Smart Mode

User controls the robot while obstacle avoidance remains active in the background.

## 🎯 Project Objective

The goal of NEXUS was to design a compact service robot capable of autonomous operation while maintaining real-time responsiveness, wireless accessibility, and efficient obstacle avoidance using low-cost hardware.

---

## 👨‍💻 Author

Ammar Shaikh

Robotics & Automation Engineer

If you found this project interesting, feel free to star the repository and connect with me.

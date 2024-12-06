# Autonomous Ship Project and Radar System

![Project Banner](path/to/your/image.png)

## 📋 Project Description
This project involves the design and construction of two components:

1. **Autonomous Ship**: A ship powered by an **Arduino Uno microcontroller** capable of navigating and avoiding obstacles using an **ultrasonic sensor (HC-SR04)** for obstacle detection. The ship adjusts its path to avoid collisions and operates autonomously.

2. **Radar System**: A radar interface that visually represents object detection and distance measurement.

---

## 🛠️ Components

### **Autonomous Ship**:
- **Arduino Uno**: The brain of the ship, controlling inputs and motors.
- **Ultrasonic Sensor (HC-SR04)**: Detects obstacles from 0-30 cm.
- **DC Motors with Fan Wheels**: Provides movement in various directions.
- **Motor Driver (L298N)**: Controls motor speed and direction.
- **Power Supply**: Batteries for the system.
- **Servo Motor**: Rotates the ultrasonic sensor for wider detection.
- **Chassis**: Lightweight plastic container to house the electronics.

### **Radar System**:
- **Radar Interface**: Displays radar sweep and detected objects.
- **Distance Measurement**: Displays detected object's distance from the sensor.

---

## 🛠️ Functional Requirements

### **Autonomous Ship**:
- **Obstacle Detection**: Detect obstacles from 0-30 cm.
- **Autonomous Navigation**: Reverse and turn when an obstacle is detected within 20 cm.
- **Motor Control**: DC motors move the ship forward, backward, left, and right.
- **Servo Motor Operation**: Rotates the ultrasonic sensor for wider coverage.
- **User Interface**: Output distance readings to the serial monitor for debugging.

### **Radar System**:
- **Radar Detection**: Detect and display objects with their distance.
- **User Interface**: Interactive display for radar sweep.

---

## 📜 Non-Functional Requirements
- **Performance**: Minimal delay in obstacle detection and navigation.
- **Reliability**: Continuous operation for at least 1 hour.
- **Usability**: Easy to set up and operate with well-documented code.
- **Safety**: Insulated electrical connections to avoid short circuits.
- **Portability**: Lightweight and easy to transport.
- **Power Efficiency**: Efficient power management to maximize battery life.

---

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Autonomous-Ship-Radar-System.git

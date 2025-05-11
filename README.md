# Obstacle-Avoiding-Robot-

This project focuses on building an autonomous robotic car capable of detecting and avoiding obstacles using an ultrasonic sensor. The goal is to create a low-cost, intelligent system that can navigate through unknown environments without human intervention, with optional control via a Bluetooth module for wireless manual override.

## How It Works:
The robot uses an ultrasonic sensor (HC-SR04) mounted at the front to continuously measure the distance between the robot and any obstacles ahead. If an object is detected within a range, the robot automatically changes its direction to avoid a collision. A Bluetooth module (HC-05) is also integrated to allow remote control and monitoring using a smartphone or other Bluetooth-enabled device.

### Technologies & Components Used:

Microcontroller: Arduino UNO (depending on implementation)

Ultrasonic Sensor (HC-SR04) – for real-time obstacle detection

Bluetooth Module (HC-05) – for wireless communication and control

DC Motors + Motor Driver (L298N) – to drive and steer the robot

Power Supply (Li-ion or 9V battery) – to power the system

Chassis with Wheels – for robotic movement

Embedded C / Arduino IDE – for firmware development

### Features:
Real-time obstacle detection and avoidance

Wireless control via mobile app (Bluetooth)

Autonomous navigation logic

Modular design for future upgrad.

### Applications:


Autonomous Vehicles – foundational concept for self-driving cars

Warehouse Robots – for navigating and transporting goods safely

Smart Wheelchairs – to avoid obstacles while moving patients

Rescue Robots – in disaster zones to move through debris

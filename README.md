# Humanoid-Bot
This project showcases a humanoid robot built on top of an RC-controlled car platform, powered by three NodeMCU modules for wireless communication and control. The humanoid structure adds functionality such as interactive movements and lighting, making it versatile for various applications.

# Project Overview
This humanoid robot combines an RC car base for mobility and a humanoid structure for interaction. The car is driven by two NodeMCU modules managing motor control and sensors, while an additional NodeMCU controls humanoid functions such as LED lights and servo movements.

# Feature
Wireless Control: Operated via Wi-Fi using ESP-NOW protocol between NodeMCU modules.
Humanoid Structure: Equipped with an interactive head panel (with LED indicators) and body.
Dual Motor Drive: Ensures smooth and precise movements.
LED Control: Visual indicators for robot status and direction.
Scalable Design: Can be enhanced with sensors, cameras, or voice control.

# Hardware Components
3x NodeMCU (ESP8266) – For wireless communication and control.
L298N Motor Driver Module – Controls the motors.
DC Motors with wheels – Provides mobility.
LiPo Battery – Powers the entire system.
Humanoid Body Structure – Built with lightweight materials.
LEDs and Resistors – For visual feedback.
Servo Motors – To move the humanoid head/arms (if applicable).
PCB (Designed in KiCad) – Custom PCB for connecting components.

# Circuit Schematic and PCB Layout
The entire circuit schematic and PCB layout were designed in KiCad, ensuring proper connections and efficient power distribution.

# Software and Libraries
Arduino IDE – For programming NodeMCU modules.
WiFi Library – For ESP8266 communication.
ESP-NOW Protocol – For peer-to-peer wireless data transfer.
Servo Library – For servo motor control.

# How It Works
1. Base (RC Car):
Controlled by two NodeMCUs for motor driving and direction control.
Communicates wirelessly with the controller NodeMCU.
2. Humanoid Structure:
LED indicators on the head for status display.
Servo motors for head/arm movement.
Operated by the third NodeMCU, which receives commands from the controller module.
3. Communication:
The controller NodeMCU sends movement and LED control commands via ESP-NOW.
The base NodeMCU handles driving, and the humanoid NodeMCU manages the upper structure.

# Assembly Steps
1. Build the RC car base using motors, NodeMCU, and motor driver.
2. Attach the humanoid body structure securely to the car base.
3. Install LEDs on the head panel and connect to NodeMCU.
4. Connect all components to the PCB and power supply.
5. Upload Arduino codes to each NodeMCU.
6. Power up and start controlling wirelessly.

# Future Enhancements
Integrate a camera for live video streaming.
Add ultrasonic sensors for obstacle detection.
Implement voice commands for control.

# Author
Narasingarao K
+917075025629
knrkondapalli123@gmail.com


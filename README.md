# VOICE CONTROLLED ROBOTIC CAR USING ARDUINO AND BLUETOOTH

## Abstract
This project presents the design and implementation of a Voice Controlled Robotic Car using Arduino Uno, HC-06 Bluetooth module, MIT App Inventor–based Android application, and L293D motor driver. The system enables wireless voice command control using a smartphone, where the spoken commands are processed by the mobile app and transmitted to the robot via Bluetooth. The Arduino interprets the commands and drives the DC motors accordingly, enabling forward, backward, left, right, and stop movement. The system successfully demonstrates real-time human–robot interaction using low-cost, easily available IoT components.

---

## 1. Introduction
Voice-controlled robotic systems are becoming increasingly relevant for smart automation, assistive technology, and human–machine interaction applications. This project aims to build a cost-effective robotic car that can be controlled through voice commands instead of traditional buttons or joysticks. By integrating Arduino with Bluetooth communication and an Android voice control app, the project provides a simple yet powerful platform to understand embedded systems, wireless communication, and robot control mechanisms.

---

## 2. Objectives
The primary objectives of this project are:
- To design a robotic car capable of receiving commands wirelessly via Bluetooth.
- To enable voice-based human interaction through a smartphone application.
- To control DC motor direction and motion using the L293D motor driver.
- To ensure smooth and stable robot movement with reliable communication.

---

## 3. Components Used
| Component | Description |
|----------|-------------|
| Arduino Uno | Main Microcontroller |
| HC-06 Bluetooth Module | Wireless Communication |
| L293D Motor Driver | Dual H-Bridge Motor Control |
| DC Gear Motors (4) | Robot Movement |
| Robot Chassis + Wheels | Mechanical Structure |
| Battery Pack | Power Supply |
| Jumper Wires / PCB | Connections |
| MIT App Inventor Android App | Voice Recognition & Command Transmission |

*A detailed Bill of Materials is available in `Hardware/BOM.md`.*

---

## 4. System Architecture
The system consists of four main functional blocks:
1. **Mobile App (MIT App Inventor)**  
   Converts user speech into command keywords and sends them to the Bluetooth module.
2. **Bluetooth Module (HC-06)**  
   Receives serial commands from the smartphone and sends them to Arduino.
3. **Arduino Uno**  
   Processes the received commands and generates control signals.
4. **Motor Driver (L293D)**  
   Controls the motors according to Arduino output to move the robot.

---

## 5. Working Principle
1. The user speaks a command such as “forward”, “backward”, “left”, “right”, or “stop” into the mobile app.
2. The MIT App Inventor app converts speech to text and maps each command to a unique control value.
3. The command is transmitted to the HC-06 Bluetooth module.
4. Arduino receives the command through serial communication.
5. Arduino activates respective motor control pins according to command.
6. L293D motor driver drives the motors to move the robot in the desired direction.

---

## 6. Arduino Firmware
Firmware is available in:
- Installable APK available in:
Firmware/end_project.ino
---

## 7. Android Application
- MIT App Inventor Source File (.aia) available in:
App/IOT_Project.aia
- Installable APK available in:
App/Releases/

## 8. Results
- Robot successfully responded to all five commands:
  - Forward  
  - Backward  
  - Left  
  - Right  
  - Stop  
- Wireless communication was stable.
- Voice response time was minimal.
- Overall system performance was reliable and consistent.

---

## 9. Challenges and Solutions
| Challenge | Solution |
|----------|----------|
| Bluetooth pairing issues | Ensured correct baud rate and pairing code |
| Power fluctuations | Used stable Li-ion supply and separate motor power |
| App speech accuracy | Optimized command recognition mapping |
| Wiring complexity | Organized wiring layout and labeling |

---

## 10. Applications
- Assistive robotics
- Home automation robots
- Educational robotics learning platform
- Voice-controlled smart vehicles
- IoT and embedded systems training

---

## 11. Future Scope
- Add obstacle detection using ultrasonic sensor
- Implement autonomous navigation
- Add camera for live monitoring
- Integrate IoT cloud-based control
- Improve AI speech recognition

---

## 12. Conclusion
The Voice Controlled Robotic Car was successfully designed and implemented using Arduino, Bluetooth communication, and a mobile voice recognition interface. The project demonstrates practical understanding of embedded systems, wireless communication, robotics, and real-time control systems. The design is low-cost, scalable, and an excellent foundation for advanced robotic applications.

---

## 15. License
This project is open-sourced under the MIT License.


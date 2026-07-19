Smart Urban Micro-Farming System

A hardware-based smart agriculture project that automates plant irrigation and artificial lighting using basic electronic components. The system is designed to improve plant growth, reduce water wastage, and minimize manual effort by continuously monitoring soil moisture and ambient light conditions.

 Overview:

Rapid urbanization has significantly reduced agricultural land while leaving many rooftops, balconies, and small open spaces unused. Plants grown in these environments often experience inconsistent watering and inadequate sunlight, leading to poor growth and unnecessary resource consumption.

The Smart Urban Micro-Farming System addresses these challenges by automatically monitoring environmental conditions and controlling irrigation and lighting without human intervention. The project demonstrates the practical application of sensors, electronic circuits, and automation techniques for sustainable urban agriculture.

 Problem Statement:

Urban plants frequently suffer from:

Inadequate sunlight exposure
Overwatering or underwatering
Excessive water consumption
Time-consuming manual monitoring
Reduced plant growth and productivity

This project provides an automated solution that ensures optimal lighting and irrigation based on real-time environmental conditions.

 Objectives:

Develop an automated irrigation system using a soil moisture sensor.
Provide artificial lighting using an LDR-based control circuit.
Reduce water wastage through intelligent pump control.
Minimize human intervention in routine plant care.
Promote sustainable and efficient urban farming.

 Key Features:

Automatic irrigation system
Intelligent lighting control
Soil moisture monitoring
Ambient light sensing
Water conservation
Energy-efficient operation
Low-cost hardware implementation
Easy to build and maintain

 Hardware Components:

LDR (Light Dependent Resistor)
Soil Moisture Sensor
555 Timer IC
BC547 NPN Transistor
Relay Module
DC Water Pump
LED
Resistors
Capacitors
Breadboard
Connecting Wires
DC Power Supply

 Working Principle:

Smart Lighting:

The Light Dependent Resistor (LDR) continuously measures ambient light intensity. When the surrounding light level falls below the required threshold, the circuit automatically switches ON the LED to provide artificial lighting. Once sufficient natural light becomes available, the LED automatically turns OFF.

Smart Irrigation:

The soil moisture sensor continuously measures soil moisture levels. When dry soil is detected, the relay activates the DC water pump to irrigate the plant. Once adequate moisture is restored, the pump is automatically switched OFF, preventing overwatering and conserving water.



 Simulation:

The electronic circuits were designed, simulated, and verified using Tinkercad before hardware implementation. Simulation helped validate circuit behavior under different environmental conditions and reduced hardware debugging time.



 Results:

The project was successfully tested under multiple operating conditions.

Automatic lighting activated correctly in low-light environments.
LED turned OFF when sufficient natural light was available.
Water pump activated only when dry soil was detected.
Pump stopped automatically after sufficient moisture was restored.
The system operated reliably without continuous manual monitoring.
Water usage was optimized through automated irrigation.



 Repository Structure:

smart-urban-micro-farming-system/
│
├── README.md
├── Images/
├── Simulation/
├── Presentation/
├── Documents/
└── Videos/



 Project Images

This repository includes:

Hardware setup
Circuit diagrams
Block diagram
Tinkercad simulation
Working photographs



 Skills Demonstrated

Electronic Circuit Design
Hardware Prototyping
Sensor Interfacing
Relay-Based Control
Analog Electronics
Hardware Testing
Circuit Simulation using Tinkercad
Automation System Design
Technical Documentation



 Future Improvements

Future versions of this project can include:

STM32-based embedded implementation
ESP32 with IoT connectivity
Mobile application for remote monitoring
OLED/LCD display
Solar-powered operation
Real-time sensor data logging
Cloud connectivity
Edge AI-based predictive irrigation
Multi-plant monitoring system



 Domain

Smart Agriculture



 Project Type

Hardware Automation Project



 License

This project is shared for educational and learning purposes. Feel free to explore, learn, and build upon the concepts presented in this repository.

# Smart-Traffic-Monitoring-System-RFID
An ESP32-based Smart Traffic Monitoring System using RFID technology for vehicle identification, speed detection, automated e-challan generation, and density-based traffic signal control.
## Overview
The Smart Traffic Monitoring System Using RFID-Based Speed Detection is an ESP32-based embedded system designed to automate vehicle speed monitoring and traffic management. The system uses RFID technology to identify vehicles, calculate their speed between two RFID checkpoints, generate e-challans for over-speeding vehicles, and control barrier access based on payment status. Additionally, IR sensors monitor traffic density and dynamically adjust traffic signal timings to improve traffic flow and reduce congestion.

## Features
- RFID-based vehicle identification
- Real-time vehicle speed detection
- Automatic e-challan generation
- RFID-based smart barrier control
- Density-based traffic signal control
- ESP32-based embedded implementation

## Hardware Components
- ESP32 Microcontroller
- RFID Readers
- RFID Tags
- IR Sensors
- Servo Motor
- LEDs
- Breadboard and Connecting Wires

## Technologies Used
- ESP32
- Arduino IDE
- Embedded C/C++
- RFID
- IoT
- Embedded Systems

## Working
1. The first RFID reader records the vehicle entry.
2. The second RFID reader records the exit.
3. ESP32 calculates the vehicle speed.
4. If the speed exceeds the predefined limit, an e-challan is generated.
5. A servo-controlled barrier grants or restricts access based on payment status.
6. IR sensors monitor traffic density and adjust signal timings dynamically.

## Applications
- Smart Traffic Management
- Highway Speed Monitoring
- Intelligent Traffic Signal Control
- Smart City Infrastructure
- Toll Plaza Automation

## Author
**Harshini Gorle**

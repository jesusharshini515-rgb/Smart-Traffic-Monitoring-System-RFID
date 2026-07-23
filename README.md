# Smart-Traffic-Monitoring-System-RFID

An ESP32-based Smart Traffic Monitoring System using RFID technology for vehicle identification, speed detection, automated e-challan generation, and RFID-based barrier control.

## Overview

The Smart Traffic Monitoring System Using RFID-Based Speed Detection is an ESP32-based embedded system designed to automate vehicle speed monitoring. The system uses RFID technology to identify vehicles, calculate their speed between two RFID checkpoints, generate e-challans for over-speeding vehicles, and control barrier access based on payment status. It provides an efficient, reliable, and cost-effective solution for intelligent traffic monitoring.

## Features

- RFID-based vehicle identification
- Real-time vehicle speed detection
- Automatic e-challan generation
- RFID-based smart barrier control
- ESP32-based embedded implementation

## Hardware Components

- ESP32 Microcontroller
- RFID Readers
- RFID Tags
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
4. If the speed exceeds the predefined limit, an e-challan is generated automatically.
5. A third RFID reader verifies the payment status.
6. The servo-controlled barrier remains closed until the fine is paid and opens after payment verification.

## Applications

- Smart Traffic Monitoring
- Highway Speed Monitoring
- Automated E-Challan Systems
- Smart City Infrastructure
- Toll Plaza Automation
## Author
**Harshini Gorle**

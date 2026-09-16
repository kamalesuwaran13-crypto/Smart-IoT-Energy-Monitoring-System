# Smart IoT Energy Monitoring and Electrical Safety System

## Project Overview

The **Smart IoT Energy Monitoring and Electrical Safety System** is an ESP32-based hardware development project designed to monitor important electrical parameters and provide real-time information about the operating condition of an electrical system. The project combines embedded systems, sensors, IoT connectivity, local monitoring, warning functions, and structured hardware project management.

The ESP32 DevKit V1 acts as the main controller. The planned prototype measures AC voltage, current, estimated power consumption, energy-use trends, and temperature. Important readings and system status are displayed locally using a 20×4 I2C LCD. The ESP32's Wi-Fi capability is also used to provide a web-based monitoring dashboard.

The system includes configurable warning logic for abnormal conditions such as over-voltage, under-voltage, excessive current, and high temperature. LEDs and a buzzer provide local warnings. A relay module is included for demonstrating controlled switching with a safe low-voltage test load during development.

> **Safety note:** This repository documents an educational prototype. Development and demonstration should use safe low-voltage test arrangements. Work involving mains electricity requires appropriate isolation, protection, equipment, and qualified supervision.

## Week 1 – Project Planning and Requirements Analysis

Week 1 focuses on developing a comprehensive plan before hardware implementation. The work includes:

- Project background, objectives, scope, and success criteria
- Functional and non-functional requirements
- Hardware and software requirements
- System architecture planning
- Risk assessment and mitigation strategies
- Eight-week project timeline and milestones
- Human and technical resource allocation
- Estimated component budget
- Development and testing strategy
- Final project deliverables

The Week 1 planning activity is structured for approximately **30–35 hours** of work.

## Planned Hardware

- ESP32 DevKit V1
- AC voltage sensor module
- Current sensor module
- Temperature sensor
- 20×4 I2C LCD
- Relay module
- Buzzer and status LEDs
- Regulated power supply
- Breadboard/prototype PCB
- Connectors, wiring, enclosure, and supporting components

## Planned Software

- Arduino IDE
- ESP32 Arduino Core
- LiquidCrystal_I2C library
- ESP32 Wi-Fi/WebServer libraries
- Web-based monitoring dashboard
- Documentation and test-record tools

## Development Roadmap

1. Requirements and architecture
2. Component selection and sourcing
3. Individual sensor testing
4. LCD and Wi-Fi development
5. Firmware module development
6. Hardware integration
7. Dashboard and alert integration
8. Calibration and functional testing
9. Final assembly
10. Validation, documentation, and demonstration

## Repository Structure

```text
Smart-IoT-Energy-Monitoring-System/
├── README.md
├── Week-1/
├── Hardware/
├── Firmware/
├── Documentation/
└── Images/
```

Additional reports, firmware, circuit documentation, test results, and project images will be added as the project progresses.

## Project Status

**Current Stage:** Week 1 – Project Planning and Requirements Analysis

## Author

**KAMALESUWARAN V**

Electronics and Communication Engineering (ECE)

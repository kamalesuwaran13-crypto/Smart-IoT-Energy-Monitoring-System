# Smart IoT Energy Monitoring and Electrical Safety System

## Electronics / Hardware Internship Project

**Prepared by:** KAMALESUWARAN V  
**Department:** Electronics and Communication Engineering (ECE)

## Project Overview

The **Smart IoT Energy Monitoring and Electrical Safety System** is an ESP32-based educational hardware project for monitoring electrical parameters, displaying system status, and demonstrating IoT-based monitoring and warning functions.

The project is being developed in stages. **Week 1** covers project planning and requirements analysis, while **Week 2** covers circuit design and simulation. Development and simulation use a safe isolated low-voltage model rather than direct mains experimentation.

## Project Objectives

- Monitor voltage and current information.
- Estimate electrical power and energy usage.
- Process measurements using an ESP32.
- Display important readings and system status locally.
- Provide IoT/web-based monitoring.
- Detect predefined abnormal operating conditions.
- Provide local warning indications.
- Develop the project using a structured hardware engineering workflow.

## Planned System Architecture

**Voltage/Current Sensing → Signal Conditioning → ESP32 → Local Display + IoT Dashboard + Warning Indicators**

The detailed measurement ranges, thresholds, component values, and protection arrangements are refined during circuit design, simulation, calibration, and prototype testing.

---

# Week 1 – Project Planning and Requirements Analysis

Week 1 establishes the engineering foundation for the project before circuit implementation.

### Week 1 Work

- Project background and problem definition
- Objectives and scope
- Functional requirements
- Non-functional requirements
- Hardware and software resource planning
- System architecture planning
- Risk identification and mitigation
- Project timeline and milestones
- Development and testing strategy
- Documentation planning

### Week 1 Outcome

A structured project plan was completed to guide circuit design, simulation, prototyping, firmware development, integration, and testing.

➡️ **[Open Week 1 Documentation](Week-1/README.md)**

---

# Week 2 – Circuit Design and Simulation

Week 2 converts the Week 1 requirements into a circuit-level concept and verifies important behaviors using a safe low-voltage simulation model.

### Week 2 Work

- Circuit architecture development
- Component selection
- Low-voltage sensing model
- Signal-conditioning concept
- ESP32 interface planning
- Simulation and analytical verification
- Threshold behavior analysis
- Circuit challenges and solutions
- Optimization recommendations
- Preparation for prototype development

### Week 2 Outcome

The Week 2 work established a safer and more testable circuit approach before physical hardware integration. Simulation results and design observations are documented separately.

➡️ **[Open Week 2 Documentation](Week-2/README.md)**  
➡️ **[Open Week 2 Simulation Analysis](Week-2/Simulation-Analysis.md)**

---

## Planned Hardware

- ESP32 DevKit V1
- Voltage sensing stage
- Current sensing stage
- Temperature sensing where required
- 20×4 I2C LCD / local display
- Buzzer and status indicators
- Relay/control stage for safe low-voltage demonstration
- Regulated low-voltage power supply
- Breadboard or prototype PCB
- Connectors and supporting passive components

## Software and Development Tools

- Arduino IDE
- ESP32 Arduino framework
- Circuit simulation/design tools
- Web/IoT monitoring interface
- GitHub for project documentation and version control

## Development Roadmap

1. **Week 1 – Planning & Requirements** – Define scope, architecture, resources, risks, and requirements.
2. **Week 2 – Circuit Design & Simulation** – Design and validate the low-voltage circuit concept.
3. **Prototype Development** – Test individual hardware modules.
4. **Firmware Development** – Implement acquisition, calculations, display, alerts, and communication.
5. **System Integration** – Combine hardware and software modules.
6. **Testing & Calibration** – Compare measurements with reference values and verify repeatability.
7. **Optimization** – Improve reliability, response, user interface, and hardware layout.
8. **Final Documentation** – Prepare results, diagrams, test records, and demonstration material.

## Repository Structure

```text
Smart-IoT-Energy-Monitoring-System/
├── README.md
├── Week-1/
│   └── README.md
├── Week-2/
│   ├── README.md
│   └── Simulation-Analysis.md
├── Hardware/          (planned)
├── Firmware/          (planned)
├── Documentation/     (planned)
└── Images/            (planned)
```

## Current Project Status

**Completed documentation stages:**
- ✅ Week 1 – Project Planning and Requirements Analysis
- ✅ Week 2 – Circuit Design and Simulation

**Next stage:** Prototype/hardware development according to the internship schedule.

## Safety Scope

This repository documents an **educational low-voltage prototype**. Simulation and prototype development should use isolated extra-low-voltage signals. Direct mains-voltage experimentation is outside the scope of these internship stages.

## Author

**KAMALESUWARAN V**  
Electronics and Communication Engineering (ECE)

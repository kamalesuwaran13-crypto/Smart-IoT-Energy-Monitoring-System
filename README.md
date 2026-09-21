# Smart IoT Energy Monitoring and Electrical Safety System

## Electronics / Hardware Virtual Internship Project

**Prepared by:** KAMALESUWARAN V  
**Department:** Electronics and Communication Engineering (ECE)  
**Internship Status:** ✅ Completed

## Project Overview

The **Smart IoT Energy Monitoring and Electrical Safety System** is an ESP32-based educational project developed during a four-week virtual internship. The project demonstrates a structured electronics and hardware development workflow for low-voltage electrical-parameter monitoring, local status display, IoT monitoring, and warning functions.

The internship was completed through four documented stages:

1. **Week 1 – Project Planning and Requirements Analysis**
2. **Week 2 – Circuit Design and Simulation**
3. **Week 3 – Prototype Assembly and Hardware Integration**
4. **Week 4 – Testing, Evaluation, and Final Documentation**

The project documentation uses an isolated extra-low-voltage educational model. Direct household-mains experimentation is outside the scope of this internship.

## Project Objectives

- Monitor voltage and current information.
- Estimate electrical power and energy usage.
- Process measurement information using an ESP32.
- Display readings and system status locally.
- Provide IoT/web-based monitoring.
- Detect predefined abnormal conditions.
- Provide warning indications.
- Apply a structured electronics/hardware engineering workflow.
- Evaluate the design through simulation-based and analytical virtual testing.

## System Architecture

**Voltage/Current Sensing → Signal Conditioning → ESP32 → Local Display + IoT Dashboard + Warning Indicators**

Exact measurement ranges, calibration values, component ratings, and physical performance would require verification during a future physical low-voltage implementation.

---

## Week 1 – Project Planning and Requirements Analysis

Week 1 established the engineering foundation of the project through problem definition, objectives, requirements, system architecture, resource planning, risk analysis, timeline development, and testing strategy.

➡️ **[Open Week 1 Documentation](Week-1/README.md)**

---

## Week 2 – Circuit Design and Simulation

Week 2 converted the requirements into a circuit-level concept and evaluated important behaviors using safe low-voltage simulation and analytical methods. It covered component selection, sensing concepts, signal conditioning, ESP32 interfacing, threshold analysis, design challenges, and optimization.

➡️ **[Open Week 2 Documentation](Week-2/README.md)**  
➡️ **[Open Week 2 Simulation Analysis](Week-2/Simulation-Analysis.md)**

---

## Week 3 – Prototype Assembly and Hardware Integration

Week 3 developed a structured prototype-integration plan covering power verification, ESP32 and display integration, sensor interfaces, alert functions, IoT connectivity, test points, integration challenges, iterative testing, and evaluation criteria.

➡️ **[Open Week 3 Documentation](Week-3/README.md)**

---

## Week 4 – Testing, Evaluation, and Final Documentation

Week 4 completed the virtual internship through simulation-based and analytical validation. It documented the test methodology, virtual test cases, performance evaluation, troubleshooting strategy, design recommendations, and final project assessment.

Because this was a virtual internship, Week 4 results are identified as **virtual/simulation-based evaluations** rather than physical laboratory measurements.

➡️ **[Open Week 4 Documentation](Week-4/README.md)**

---

## Planned Hardware Architecture

- ESP32 DevKit V1
- Low-voltage voltage-sensing stage
- Low-voltage current-sensing stage
- Temperature sensing where required
- 20×4 I2C LCD / local display
- Buzzer and status indicators
- Low-voltage relay/control demonstration stage
- Regulated low-voltage power supply
- Breadboard/prototype PCB concept
- Connectors and supporting passive components

## Software and Development Tools

- Arduino IDE
- ESP32 Arduino framework
- Circuit simulation/design tools
- Analytical calculation methods
- Web/IoT monitoring concept
- GitHub for documentation and version control

## Completed Internship Workflow

| Week | Task | Status |
|---|---|---|
| Week 1 | Project Planning and Requirements Analysis | ✅ Completed |
| Week 2 | Circuit Design and Simulation | ✅ Completed |
| Week 3 | Prototype Assembly and Hardware Integration | ✅ Completed |
| Week 4 | Testing, Evaluation, and Final Documentation | ✅ Completed |

## Repository Structure

```text
Smart-IoT-Energy-Monitoring-System/
├── README.md
├── Week-1/
│   └── README.md
├── Week-2/
│   ├── README.md
│   └── Simulation-Analysis.md
├── Week-3/
│   └── README.md
└── Week-4/
    └── README.md
```

## Final Project Status

✅ **Virtual internship completed successfully.**

All four internship stages are documented in this repository. The project progressed from initial planning and requirements through circuit design, simulation, prototype-integration planning, and final virtual testing/evaluation.

### Future Scope

A future physical development stage may include:
- Building the complete isolated low-voltage prototype.
- Calibration against suitable reference equipment.
- Custom PCB design.
- Improved analog/digital grounding and filtering.
- Extended reliability and repeatability testing.
- Enclosure and connector development.
- Further IoT dashboard and data-logging improvements.

## Safety Scope

This repository documents an **educational extra-low-voltage project**. Direct household-mains wiring, probing, or experimentation is not part of the internship work. Any future physical implementation should use appropriate isolation and undergo a separate safety review for its intended application.

## Author

**KAMALESUWARAN V**  
Electronics and Communication Engineering (ECE)

---

**Internship Project Status: COMPLETED**

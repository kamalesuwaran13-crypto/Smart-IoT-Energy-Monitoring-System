# Week 1 – Project Planning and Requirements Analysis

## Project Title
**Smart IoT Energy Monitoring and Electrical Safety System**

## Week 1 Objective
The Week 1 task focused on planning a hypothetical electronics/hardware project, defining its purpose and requirements, identifying the required resources, analyzing risks, and preparing a structured development schedule.

## Project Overview
The Smart IoT Energy Monitoring and Electrical Safety System is designed as an educational IoT-based prototype for monitoring electrical parameters and identifying abnormal operating conditions. The system concept combines voltage/current sensing, an ESP32 controller, local indication, and IoT monitoring.

For development and simulation, the project uses a safe isolated low-voltage model rather than direct mains experimentation.

## Main Objectives
- Develop an IoT-based electrical energy monitoring concept.
- Monitor voltage and current information.
- Estimate electrical power and energy usage.
- Provide local and remote monitoring.
- Detect defined abnormal electrical conditions.
- Provide warning/alert indications.
- Maintain a modular architecture for future expansion.

## Functional Requirements
1. Acquire voltage and current sensor data.
2. Process measurements using the ESP32.
3. Calculate relevant electrical parameters.
4. Display system status locally.
5. Send monitoring information to an IoT interface.
6. Detect predefined abnormal conditions.
7. Activate visual/audible alerts where appropriate.
8. Support periodic data updates.

## Non-Functional Requirements
- Safe low-voltage development and simulation.
- Reliable and repeatable measurements.
- Clear and understandable user interface.
- Modular hardware and firmware.
- Reasonable prototype cost.
- Maintainable code and documentation.
- Expandable architecture.

## Preliminary Hardware
- ESP32 development board
- Voltage sensing stage
- Current sensing stage
- Display module
- Buzzer / status indicators
- Supporting resistors, capacitors and connectors
- Regulated low-voltage power supply
- Breadboard/prototyping hardware

## Software and Tools
- Arduino IDE
- ESP32 Arduino framework
- Circuit simulation/design software
- IoT dashboard/web interface
- GitHub for version control and documentation

## Risk Analysis
| Risk | Possible Impact | Planned Mitigation |
|---|---|---|
| Incorrect sensor readings | Inaccurate monitoring | Calibration and reference measurements |
| Electrical noise | Unstable values | Filtering and careful circuit layout |
| Power supply instability | Controller resets/errors | Proper regulated supply and decoupling |
| Communication failure | Missing remote data | Local status display and reconnection logic |
| Unsafe voltage exposure | Hardware/user risk | Use isolated low-voltage development model |
| Firmware errors | Incorrect calculations | Modular testing and validation |

## Development Plan
### Phase 1 – Planning
Define the problem, objectives, requirements, resources, risks, and project scope.

### Phase 2 – Circuit Design and Simulation
Develop the safe low-voltage circuit model, select components, simulate measurement stages, and document results.

### Phase 3 – Prototype Development
Build and test individual hardware modules before system integration.

### Phase 4 – Firmware Development
Implement sensor acquisition, calculations, alerts, display, and IoT communication.

### Phase 5 – Integration and Testing
Combine modules and verify measurement accuracy, reliability, communication, and alert behavior.

### Phase 6 – Optimization and Documentation
Improve performance, organize project files, document results, and prepare final deliverables.

## Week 1 Deliverables
- Project concept and scope
- Problem statement
- Objectives
- Functional and non-functional requirements
- Hardware/software resource plan
- Risk analysis
- Development phases and timeline
- Testing strategy
- Project documentation plan

## Week 1 Outcome
Week 1 established a structured foundation for the Smart IoT Energy Monitoring and Electrical Safety System. The requirements and planning outputs are used as the basis for Week 2 circuit design and simulation.

## Safety Note
This internship project is treated as an educational prototype. Development and simulation should use isolated extra-low-voltage signals. Direct mains-voltage experimentation is outside the scope of the Week 1/Week 2 prototype work.

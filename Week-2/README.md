# Week 2 - Circuit Design and Simulation

## Objective
Week 2 converts the Week 1 project plan into a circuit-level design for the Smart IoT Energy Monitoring and Electrical Safety System. The work focuses on circuit architecture, component selection, safe low-voltage simulation, performance analysis, design challenges, and optimization recommendations.

## Safety Scope
The educational simulation uses an isolated 12 VAC low-voltage source model. No direct mains wiring is required. Any future mains-rated implementation requires certified isolation/protection and qualified supervision.

## Week 2 Deliverables
- Proposed circuit architecture
- Component selection and justification
- Safe low-voltage simulation model
- ADC signal-range analysis
- Temperature warning-threshold analysis
- Design challenges and solutions
- Hardware optimization recommendations
- 33-hour work breakdown

## Key Simulation Result
The modeled voltage-sensing output is centered at 1.65 V with a 1.20 V peak swing, giving an approximate ADC range of 0.45 V to 2.85 V. This remains within the intended 0-3.3 V ESP32 ADC domain with useful headroom.

## Status
Week 2 documentation prepared. The next stage is controlled low-voltage prototyping, calibration, and firmware integration.

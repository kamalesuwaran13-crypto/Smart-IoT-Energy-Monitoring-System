# Week 2 Simulation Analysis

## Test Model
- Source: isolated 12 Vrms AC model
- Frequency: 50 Hz
- ESP32 ADC design domain: 0 to 3.3 V
- Sensing waveform midpoint: 1.65 V
- Modeled sensing peak swing: 1.20 V
- Example temperature warning threshold: 55 °C

## Results
| Test | Expected | Model result | Assessment |
|---|---|---|---|
| AC source | 12 Vrms, 50 Hz | approximately ±16.97 V peak | Correct sinusoidal model |
| ADC sensing output | remain within 0-3.3 V | approximately 0.45-2.85 V | Pass |
| Midpoint bias | approximately 1.65 V | 1.65 V | Pass |
| Temperature warning | activate at 55 °C | transition at 55 °C | Pass |

## Analysis
The proposed conditioning concept provides ADC headroom and represents an AC waveform as a unipolar signal suitable for controller-side sampling. Real hardware performance will depend on sensor selection, calibration, noise, ADC characteristics, component tolerance, power-supply quality, and PCB layout.

## Design Challenges
Important issues for the next stage include ADC over-voltage protection, electrical noise, sensor tolerance, supply stability, relay transients, I2C compatibility, and safe electrical isolation.

## Optimization
Use filtering and averaging, stable regulation and decoupling, proper relay/buzzer drivers, calibration against trusted instruments, and adequate ADC headroom. Any future mains-rated implementation must use appropriate certified isolation and protection practices.

> Note: The Week 2 DOCX uses analytical simulation plots for design validation. They are not presented as LTspice or Multisim screenshots. If a named simulator is mandatory, genuine screenshots should be captured from that simulator and added to the report.

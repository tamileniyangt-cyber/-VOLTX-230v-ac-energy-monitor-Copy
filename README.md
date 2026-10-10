# VOLTX — 230V AC Energy Monitor PCB

**A KiCad PCB design project for monitoring AC voltage, current, power, and energy in a 230V AC electrical system.**

![Project Status](https://img.shields.io/badge/Project-In%20Development-orange)
![PCB Design](https://img.shields.io/badge/PCB-4--Layer-blue)
![Input](https://img.shields.io/badge/AC%20Input-230V%20AC-red)
![EDA Tool](https://img.shields.io/badge/EDA-KiCad-314CB0)

---

## 📌 Project Overview

The **VOLTX 230V AC Energy Monitor** is a printed circuit board (PCB) development project designed to measure and monitor electrical parameters in an AC power system.

The project focuses on PCB design, voltage and current sensing, power and energy measurement, and electrical isolation between hazardous mains circuitry and accessible low-voltage electronics.

The PCB is being developed using KiCad with a four-layer board structure and a reinforced-isolation design objective.

> **Important:** Reinforced isolation is a design requirement, not a claim of certified safety. The finished design must be verified against applicable safety standards before being connected to mains power.

## 🎯 Project Objectives

- Design a PCB for a 230V AC energy-monitoring application.
- Measure AC voltage and load current.
- Support real-power and energy calculations.
- Develop a suitable low-voltage power architecture.
- Separate mains-voltage and low-voltage circuitry.
- Implement appropriate creepage, clearance, and isolation-barrier requirements.
- Prepare the schematic, PCB layout, bill of materials (BOM), and manufacturing outputs.

## ⚙️ Planned Features

- AC voltage measurement
- AC current measurement
- Real-power measurement
- Energy-consumption calculation
- Power-factor measurement, if supported by the selected metering architecture
- Four-layer PCB layout
- Reinforced isolation design
- Future microcontroller-based monitoring, depending on the final architecture

*Features depend on the final schematic, selected components, firmware, and validation results.*

## 🧩 Hardware Design

| Parameter | Design information |
|---|---|
| Application | AC energy monitoring |
| Nominal AC input | 230V AC |
| PCB construction | 4 layers |
| Isolation objective | Reinforced isolation |
| EDA software | KiCad |
| Voltage-sensing method | To be finalized |
| Current-sensing method | To be finalized |
| Metering IC | To be selected or confirmed |
| Microcontroller | To be selected or confirmed |
| Maximum load current | To be specified |
| PCB dimensions | To be finalized |

## 🔌 System Architecture

The intended system is organized into the following functional sections:

1. **AC input and protection** — input terminals and appropriately rated overcurrent and surge protection.
2. **Voltage sensing** — a suitably rated sensing circuit or isolated measurement device.
3. **Current sensing** — a current transformer, shunt-based solution, or other suitable sensing method, depending on the final design.
4. **Energy measurement** — a metering IC or other validated measurement architecture.
5. **Low-voltage power supply** — a suitable supply with the required safety isolation.
6. **Processing and communication** — optional microcontroller, display, or communication interfaces.
7. **PCB isolation barrier** — separation between mains-referenced circuitry and accessible low-voltage circuitry.

The final architecture and component choices will be documented after the schematic is finalized.

## 🛠️ Tools and Software

- **KiCad EDA** — schematic capture and PCB layout
- Datasheets and component application notes
- PCB design-rule checking (DRC)
- Electrical-rule checking (ERC)
- Manufacturing and assembly documentation tools

## 📁 Repository Structure

```text
-VOLTX-230v-ac-energy-monitor-Copy/
├── README.md
├── hardware/
│   ├── schematic/
│   ├── pcb/
│   ├── libraries/
│   └── manufacturing/
├── documentation/
│   ├── datasheets/
│   ├── design-notes/
│   └── test-reports/
└── LICENSE
```

*This is a suggested structure. Add folders and files as they are created in your project.*

## 🧪 Development Status

- [x] Project concept established
- [x] Four-layer PCB selected as the design approach
- [x] Reinforced isolation identified as a requirement
- [ ] Finalize the power-supply architecture
- [ ] Finalize the voltage- and current-sensing circuits
- [ ] Select and verify component ratings
- [ ] Complete schematic ERC
- [ ] Complete PCB layout and DRC
- [ ] Verify creepage and clearance distances
- [ ] Review thermal performance and fault protection
- [ ] Manufacture and inspect the PCB
- [ ] Perform appropriate electrical safety and functional validation
- [ ] Document measured accuracy and power consumption

## ⚠️ Electrical Safety

**WARNING: HAZARDOUS MAINS VOLTAGE — 230V AC CAN CAUSE FATAL ELECTRIC SHOCK OR FIRE.**

This project is intended for engineering development. An unverified PCB must not be connected directly to mains power.

Before manufacturing or testing, verify:

- Applicable insulation and electrical safety standards
- Required creepage and clearance distances for the working voltage, transient conditions, pollution degree, and material group
- Isolation ratings of power supplies, sensing devices, and other components
- Input fusing and fault protection
- PCB spacing, slots, copper keep-outs, and isolation barriers
- Enclosure, terminals, and protection against accidental contact
- Functional performance and safety using appropriate test equipment and qualified procedures

A four-layer PCB does not automatically provide reinforced isolation. The complete design and its components must meet the applicable requirements.

## 📊 Measurements and Results

Actual measurements will be added after the design is built and validated.

| Measurement | Result |
|---|---|
| AC input voltage | Pending validation |
| Load current | Pending validation |
| Real power | Pending validation |
| Energy measurement | Pending validation |
| Standby power consumption | Pending validation |
| Measurement accuracy | Pending validation |
| Thermal performance | Pending validation |

## 🚀 Future Improvements

- Display of voltage, current, power, and energy
- Data logging and energy-use reports
- Optional wireless monitoring
- Calibration and measurement-error analysis
- Improved documentation and manufacturing files

These are possible future improvements, not confirmed implemented features.

## 📄 License

The appropriate license will be specified once the project's sharing and redistribution terms are decided. For an open-source hardware project, consider a suitable CERN Open Hardware Licence.

## 👨‍💻 Project

**Project name:** VOLTX 230V AC Energy Monitor PCB  
**Design software:** KiCad  
**Project status:** In development

---

*Designed with a focus on measurement, PCB engineering, and electrical safety.*

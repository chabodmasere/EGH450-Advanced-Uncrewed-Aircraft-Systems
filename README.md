# EGH450 - Advanced Uncrewed Aircraft Systems

<p align="center">
  <img 
    src="https://github.com/user-attachments/assets/ed56d43b-d1c8-477d-8eb3-1ae39d0d7b91" 
    alt="EGH450 UAV Project Screenshot" 
    width="650"
  />
</p>

<p align="center">
  <em>Airframe, power, and propulsion subsystem development for an advanced uncrewed aircraft platform.</em>
</p>

---

## Overview

This repository contains my project artefacts for **EGH450 Advanced Uncrewed Aircraft Systems**, focused on the **airframe, power, and propulsion subsystems** of an uncrewed aircraft platform.

The project involved UAV subsystem design, structural analysis, CAD modelling, 3D-printable component development, power-system packaging, and motor bench testing.

The aim was to evaluate how mechanical design, onboard power integration, and propulsion performance affect the overall capability of an uncrewed aircraft system.

---

## Project Summary

Uncrewed Aircraft Systems require the integration of multiple engineering domains, including:

* Aerospace structures
* Propulsion systems
* Power electronics
* Embedded systems
* Autonomous-system hardware
* Mechanical packaging
* Physical prototyping

My work focused on three major subsystem areas:

1. **Airframe Design**
2. **Power System Integration**
3. **Propulsion System Testing**

These areas directly influence UAV mass, endurance, stability, payload integration, manufacturability, and mission performance.

---

## Repository Contents

```text
EGH450-Advanced-Uncrewed-Aircraft-Systems/
│
├── images/
│   └── Project images, renders, and supporting visuals
│
├── 3D_Print.stl
├── final.stl
├── battery_case.stl
├── pi_case.stl
├── raspberry_pi_case.stl
│
├── STATIC TEST.f3d
├── Airframe_Analysis.wbpj
├── Motor_bench_test.xls
│
└── README.md
```

---

## Project Focus Areas

### 1. Airframe Design

The airframe is the primary structural foundation of the UAV. It determines how the propulsion system, battery system, avionics, payload, and supporting hardware are physically arranged and supported.

My airframe work focused on structural layout, component packaging, manufacturability, and mechanical integration.

#### Key Considerations

* UAV structural layout
* Component placement
* Centre of gravity considerations
* Battery and electronics mounting
* Propulsion mounting requirements
* Manufacturability
* 3D-printable component design
* Structural stiffness and mechanical suitability
* Weight distribution
* Practical assembly constraints

#### Relevant Files

| File                     | Description                               |
| ------------------------ | ----------------------------------------- |
| `3D_Print.stl`           | 3D-printable UAV component model          |
| `final.stl`              | Finalised 3D model component              |
| `STATIC TEST.f3d`        | Fusion 360 static test / CAD design file  |
| `Airframe_Analysis.wbpj` | ANSYS Workbench airframe analysis project |

---

### 2. Power System Integration

The power system is responsible for supplying energy to the UAV propulsion system, onboard computer, sensors, communication modules, and supporting electronics.

For this project, the power-system work focused on the physical packaging and integration of onboard electrical components, especially the battery and Raspberry Pi enclosure.

#### Key Considerations

* Battery enclosure design
* Electrical hardware packaging
* Onboard computer protection
* Power-system accessibility
* Mechanical protection of electronics
* Integration with the airframe
* Weight and volume trade-offs
* Safe component mounting
* Maintainability

#### Relevant Files

| File                    | Description                              |
| ----------------------- | ---------------------------------------- |
| `battery_case.stl`      | 3D-printable battery enclosure           |
| `pi_case.stl`           | Onboard computer / Raspberry Pi case     |
| `raspberry_pi_case.stl` | Alternative Raspberry Pi enclosure model |

---

### 3. Propulsion System Testing

The propulsion system provides the thrust required for UAV flight. Propulsion performance directly affects take-off capability, climb rate, cruise efficiency, endurance, and payload capacity.

The propulsion component of this project involved motor bench testing and performance evaluation.

#### Key Considerations

* Motor performance
* Propeller suitability
* Thrust generation
* Power draw
* Motor efficiency
* Electrical load
* Propulsion-to-weight relationship
* Bench test data collection
* Propulsion-system suitability for UAV operation

#### Relevant Files

| File                   | Description                                              |
| ---------------------- | -------------------------------------------------------- |
| `Motor_bench_test.xls` | Motor bench test data and propulsion performance results |

---

## System-Level Integration

The airframe, power system, and propulsion system are tightly coupled. A UAV cannot be designed by treating these subsystems independently.

```text
Airframe Geometry
      ↓
Structural Mass and Component Layout
      ↓
Battery and Electronics Placement
      ↓
Centre of Gravity and Weight Distribution
      ↓
Required Thrust and Power
      ↓
Motor and Propeller Performance
      ↓
Flight Endurance and Mission Capability
```

A heavier airframe increases thrust demand. A larger battery can increase endurance, but also increases aircraft mass. A more powerful propulsion system can improve thrust capability, but may increase current draw and reduce flight time.

The final UAV design must therefore balance structure, power, propulsion, and mission requirements.

---

## Engineering Trade-Offs

| Design Area           | Trade-Off                                   |
| --------------------- | ------------------------------------------- |
| Airframe              | Structural strength vs weight               |
| Battery System        | Energy capacity vs mass                     |
| Propulsion            | Thrust capability vs efficiency             |
| Electronics Packaging | Protection vs accessibility                 |
| 3D Printing           | Manufacturability vs structural performance |
| Component Layout      | Compact packaging vs maintainability        |
| System Integration    | Performance vs complexity                   |

---

## Tools Used

| Tool            | Purpose                                        |
| --------------- | ---------------------------------------------- |
| Fusion 360      | CAD modelling and static design work           |
| ANSYS Workbench | Airframe structural analysis                   |
| Microsoft Excel | Motor bench test data analysis                 |
| STL File Format | 3D-printable component models                  |
| 3D Printing     | Physical prototyping and component fabrication |

---

## Skills Demonstrated

This project demonstrates capability in:

* UAV airframe design
* Aerospace subsystem integration
* Power-system packaging
* Propulsion testing
* Motor bench test analysis
* CAD modelling
* 3D-printable component design
* Static structural analysis
* Mechanical prototyping
* Engineering documentation
* Design trade-off evaluation
* Autonomous aircraft hardware integration

---

## Applications

The engineering principles demonstrated in this project apply to:

* Autonomous UAVs
* Small uncrewed aircraft
* Electric aircraft platforms
* Remote sensing UAVs
* Search and rescue drones
* Infrastructure inspection drones
* Aerospace robotics
* Experimental flight vehicles
* Embedded autonomy platforms

---

## Author

**Chabod Masere**

🎓 **Bachelor of Engineering, Electrical & Aerospace**
🎓 **Master of Robotics and Artificial Intelligence**

---

## Portfolio Context

This project forms part of my broader engineering portfolio across:

* Aerospace systems
* Robotics
* Autonomous vehicles
* Electrical systems
* Physical AI
* Control and propulsion systems
* System-level engineering design

# 3D-Printed Modular Tricopter Tiltrotor VTOL UAV

A custom-built, transition-capable Unmanned Aerial Vehicle (UAV) featuring a unique tricopter tiltrotor design. This project encompassed the full development stack: aerodynamic simulation, airframe design, custom PCB fabrication, embedded C++ programming, and flight testing.

<img width="1056" height="546" alt="image" src="https://github.com/user-attachments/assets/8ea3ebc6-3ad2-4d5e-8b21-1947d32edd70" />


## 🚀 Project Overview

This project was independently developed to explore the challenges of Vertical Take-Off and Landing (VTOL) aircraft, specifically the control dynamics of transition flight between hover and forward flight. The goal was to design, build, and program a robust low-cost, modular UAV system from the ground up.

## ⚙️ Technical Specifications

| System | Components & Technologies |
| :--- | :--- |
| **Airframe** | Custom 3D-printed (PLA/CF-Nylon) structure, carbon fiber reinforcement, proprietary tilt mechanism design. |
| **Avionics** | Custom 4-layer PCB, **Teensy 4.1** Microcontroller, **MPU6050** IMU, **NEO-M8N** GPS Module, **GY-273** Magnometer, **BMP-388** Barometer, Airspeed Sensor |
| **Software** | C++ (Flight Control Firmware), MATLAB (Transition Simulation), PID Control Loops, OneShot125 Protocol. |
| **Power** | 4S LiPo Battery, UBEC Voltage Regulation, PDB Board. |
| **Simulation & Design** | **Autodesk CFD** (Aerodynamic Analysis), **Onshape/Fusion 360** (CAD), **KiCAD** (PCB Design). |
| **Payload** | Integrated **FLIR Lepton 3.5** Radiometric Thermal Imaging Sensor. |
## 🛠️ Key Features

*   **Custom Flight Controller:** Real-time PID control loops written in C++ for stable attitude control.
*   **Novel Airframe Design:** A modular, fully 3D-printed tiltrotor tricopter employing unified servo-actuated mechanisms to enable a mechanically simple and aerodynamically stable transition between hover and forward flight.
*   **Transition Mechanism:** Designed and fabricated a novel tiltrotor system to smoothly transition between hover and forward flight.
*   **Ansys CFD Validation:** Aerodynamic profiles were simulated and optimized prior to fabrication.
*   **Integrated Thermal Payload:** Successfully incorporated a FLIR Lepton thermal camera for potential applications in search & rescue or inspection.

## 🎯 Project Status

**Current Phase:** Flight Testing & PID Tuning
*   [ ] Stable Hover Achieved
*   [ ] Successful Transition Sequence
*   [ ] Fully Autonomous Flight
*   [] All Subsystems Bench-Tested
*   [] Custom PCB Fabricated & Populated

## 📸 Media
<img width="1063" height="676" alt="image" src="https://github.com/user-attachments/assets/2da4c5cc-d567-4d72-b708-6d02e8497cbd" />


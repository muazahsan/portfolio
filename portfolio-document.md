# Master Engineering Portfolio & Technical Documentation
## Muaz Ahsan P — Robotics, Motion Control & Embedded Systems Engineer

---

## 1. Professional Identity & Contact

- **Full Name:** Muaz Ahsan P
- **Specialization:** Robotics Software, Forward/Inverse Kinematics, Industrial Motion Control, 3D Concrete Printing (3DCP), Embedded Firmware
- **Phone:** +91 9952721473
- **Email:** [muazahsan.p@gmail.com](mailto:muazahsan.p@gmail.com)
- **Location:** Tamil Nadu, India
- **LinkedIn:** [linkedin.com/in/muazahsan](https://linkedin.com/in/muazahsan)
- **GitHub:** [github.com/muazahsan](https://github.com/muazahsan)
- **Patent:** Published Indian Patent Applicant (Adaptive Custom Lighting System)

---

## 2. Professional Summary

Electronics and Communication Engineering graduate specializing in Robotics, Industrial Automation, and Embedded Systems. Demonstrated proficiency in Motion Control, Industrial Robot Kinematics, and Hardware–Software Integration. Key engineering accomplishments include:
1. **Kelvin6k Atom V2:** Built end-to-end forward/inverse kinematics solvers, custom trajectory planners, operator control console, and Inovance SV670N servo drive integration over EtherCAT, tuning closed-loop feedback to achieve **0.48° operational precision**.
2. **Kelvin6k Multi-Robot 3DCP:** Developed and debugged motion control software across three construction 3D printer platforms:
   - **Atom V1:** Mobile polar-coordinate cylindrical 3DCP printer with custom Cartesian-to-Polar G-code translation.
   - **Aton:** India's largest SCARA robotic arm concrete 3D printer for industrial-scale building construction.
   - **Stationary Gantry:** Large multi-axis Cartesian system for modular structural component manufacturing.
3. **Patent Holder:** Indian Patent Application No: 202441001806 A (*A System for Adaptive Custom Lighting*).
4. **Embedded & Software Products:** Author of Speedzy ERP (Python/PySide6/SQLite), Pre-Order Canteen Web App (React/Vite/Firestore), and ESP32 Quadruped Robot.

---

## 3. Education

- **Degree:** Bachelor of Technology (B.Tech) in Electronics & Communication Engineering (ECE)
- **Institution:** B.S. Abdur Rahman Crescent Institute of Science & Technology, Chennai, India
- **Duration:** 2022 – 2026
- **CGPA:** 7.4 / 10
- **Key Coursework & Lab Focus:** Robot Kinematics, Industrial Automation, Embedded C, Microcontrollers, Motion Planning, Control Systems

---

## 4. Patents & Intellectual Property

### A System for Adaptive Custom Lighting
- **Application Number:** 202441001806 A
- **Jurisdiction:** Indian Patent Office
- **Status:** Published (April 2025)
- **Summary:** Intelligent embedded lighting management system combining ambient sensor telemetry and real-time adaptive control algorithms to dynamically optimize illumination profiles according to physical human presence and daylight variations.

---

## 5. Work Experience

### 5.1 Kelvin6K Technologies Pvt. Ltd.
**Title:** Robotics & Software Developer (Full-Time Trainee)  
**Timeline:** Dec 2025 – Sep 2026  
**Location:** Chennai, India  
**Scope & Core Responsibilities:**
- **Large-Scale 3DCP Robot Construction:** Key software and motion-control engineer on industrial construction 3D printers, executing real-world building structures and full-scale concrete walls.
- **Cartesian-to-Joint Kinematics:** Developed custom robot kinematics translating slicer-generated Cartesian G-code $(X, Y, Z)$ directly into multi-axis joint movements and smooth trajectory commands.
- **Deterministic Motion Execution:** Configured **Linux Real-Time Kernel (PREEMPT_RT)** for low-jitter motion control; integrated Inovance SV670N AC servo drives over EtherCAT fieldbus.
- **Joint Alignment & Calibration:** Performed absolute optical encoder calibration, axis squareness alignment, home offsets, and closed-loop PID servo tuning.
- **Workspace Constraints & Safety:** Implemented robot workspace envelope boundaries, velocity/acceleration soft limits, and emergency stop interlock routines.
- **Dual Fabrication Capabilities:** Integrated continuous 3D concrete printing and CNC subtractive machining workflows.
- **Field Hardware Troubleshooting:** Diagnosed mechanical backlash, servo drive alarm codes, and communication timeouts during live on-site construction prints.

**Title:** Robotics & Software Developer Intern  
**Timeline:** Feb 2025 – Dec 2025  
**Location:** Chennai, India  
**Scope & Core Responsibilities:**
- **Atom V2 4-Axis Palletizer Robot:** Engineered the complete analytical forward/inverse kinematics (FK/IK) solvers, trajectory planning, and operator GUI console, tuning closed-loop feedback to achieve **0.48° operational precision**.
- **Multi-Robot 3DCP Platforms:**
  - *Atom V1 (Polar):* Developed Cartesian-to-Polar G-code translation engine with dynamic inverse-radius velocity scaling ($v = \omega \cdot R$) to ensure consistent layer bead width.
  - *Aton (SCARA):* Programmed and tuned India's largest SCARA concrete 3D printing arm for on-site wall construction.
  - *Stationary Gantry:* Configured multi-axis Cartesian stepper/servo coordination and axis squareness calibration.
- **Extrusion & Slurry Coordination:** Integrated closed-loop pump dosing motors with nozzle toolhead speeds to avoid bead thinning or over-extrusion during direction changes.

### 5.2 Speedzy
**Title:** Operations Lead & Software Developer  
**Timeline:** May 2025 – Jun 2026  
**Scope & Core Responsibilities:**
- Led daily delivery operations coordinating restaurant vendors, riders, and customers.
- Engineered the **Speedzy Management System**, a standalone desktop ERP in Python, PySide6, and SQLite, automating order reconciliation, driver commission calculations, and ReportLab PDF statement generation.

---

## 6. Technical Skills Matrix

| Category | Primary Technologies & Competencies |
|---|---|
| **Robotics & Motion Control** | Forward/Inverse Kinematics, Palletizer Geometry, SCARA Kinematics, Polar G-Code Translation, Trajectory Planning, Workspace Envelope Analysis, LinuxCNC, ROS 2 (Exploring) |
| **Industrial Drives & Fieldbus** | Inovance SV670N & SV660N, EtherCAT Protocol, RS485 / Modbus RTU, High-Resolution Optical Encoders, Servo Tuning, 0.48° Precision Calibration, Closed-Loop PID |
| **3DCP & Machine Platforms** | Concrete 3D Printing (3DCP), Kelvin6k Atom V2 (Palletizer), Kelvin6k Atom V1 (Polar), Kelvin6k Aton (SCARA), Stationary Gantry Systems, Extrusion Pump Synchronization |
| **Embedded & Microcontrollers** | ESP32, Arduino Uno, Raspberry Pi, Embedded C, UART, USB-to-UART, Sensor Interfacing, Keil uVision, STM32CubeProgrammer |
| **Programming & OS** | C++, Python, C, Bash Scripting, Linux (Ubuntu), Git / GitHub, MATLAB / Simulink, NI Multisim |
| **Software, Web & AI** | PySide6 (Qt), SQLite, React, Vite, Tailwind CSS, Firebase Firestore, Cursor AI, Local LLM Inference (llama2.c on MCU), OpenClaw |

---

## 7. Detailed Engineering Projects (Tiered Architecture)

### Tier 1: Flagship Industrial Robotics & Motion Control

#### 7.1 Kelvin6k Atom V2: 4-Axis Palletizer Robot (Primary Showcase)
- **Problem Solved:** Designing, calculating, and physically deploying a rigid 4-axis industrial palletizer robot capable of sorting, stacking, and concrete extrusion with high joint accuracy.
- **End-to-End System Architecture:**
  `UI Console (PySide6 / C++)` $\to$ `Motion Planner / Kinematics (FK/IK)` $\to$ `Fieldbus (EtherCAT PREEMPT_RT)` $\to$ `Inovance SV670N AC Drives` $\to$ `Motor Optical Encoders (0.48° Closed-Loop)`
- **My Work:**
  1. Formulated analytical Forward and Inverse Kinematics equations in Python and C++.
  2. Implemented trajectory interpolation algorithms for smooth velocity and acceleration profiles.
  3. Built the complete graphical operator console for manual jogging, coordinate readouts, toolpath visualization, and G-code execution.
  4. Interfaced Inovance SV670N AC servo drives over an EtherCAT fieldbus, calibrating motor poles, encoder pulses per revolution, and tuning PID gains to reach **0.48° positioning precision**.
- **Result:** Successfully validated and demonstrated on physical hardware at Kelvin6k with live axis jogging video.

#### 7.2 Kelvin6k Multi-Robot 3DCP & Polar G-Code Translation
- **Problem Solved:** Construction 3D printers rely on standard slicing software (Cura, PrusaSlicer) that produce Cartesian (X, Y, Z, E) G-code. A polar or SCARA machine requires mathematical coordinate transformation without distorting extrusion feed rates.
- **My Work:**
  1. Developed a robust Cartesian-to-Polar translator mapping $X, Y \to R, \theta$ with radius constraints and continuous rotational unwrapping.
  2. Implemented angular velocity scaling where feed rate $F$ is modulated inversely to radius $R$ ($v = \omega \cdot R$) to prevent nozzle stutter and uneven extrusion.
  3. Commissioned control software on the Kelvin6k Atom V1 (cylindrical 3DCP), Aton (SCARA 3DCP), and stationary gantry.
  4. Executed live continuous concrete wall printing on outdoor construction sites.

---

### Tier 2: Autonomous Mechatronics & Edge-AI Systems

#### 7.3 Edge-AI Traffic Management & NavIC Offline Navigation
- **Problem Solved:** Emergency vehicles delayed in traffic jams during network blackouts.
- **System Architecture:** Offline routing using local OpenStreetMap tiles and NavIC/GNSS positioning, paired with an edge-AI traffic signal controller on Raspberry Pi.
- **Validation:** Functional hardware testbed built with LEDs and map layout; reviewed and demonstrated to **Kerala Police**, who provided positive feedback and technical validation.

#### 7.4 ESP32 Quadruped Walking Robot
- **System Architecture:** 8-DOF servo-driven quadruped robot with inverse kinematic gait control and balance stability algorithms. Verified with live walking test videos.

#### 7.5 Foundational Mechatronics & Lab Builds
- **Multirotor Drone (2022):** Flight controller tuning, ESC telemetry, and telemetry calibration at Crescent Propulsion Lab.
- **Smart Pill Box + E-Med App:** Embedded medication adherence box with buzzer/LCD and companion mobile tracking dashboard.
- **Automated Egg Incubator:** Closed-loop temperature and humidity incubator with relay heating controls and turners (verified with successful chick/duckling hatching).
- **Arduino Uno Interactive Arcade Game:** Multiplexed LED matrix arcade game on ATmega328P using hardware timer interrupts.

---

### Tier 3: Collapsible Software Systems (Rapid AI-Assisted Builds)

#### 7.6 Speedzy Management System (Desktop ERP)
- **Problem Solved:** Manual record keeping and reconciliation errors across delivery riders and restaurant vendors.
- **Tech Stack:** Python 3, PySide6 (Qt6), SQLite, Matplotlib, ReportLab. Built rapidly using AI-assisted workflow.
- **Features:** Vendor ledger, rider payout calculator, interactive revenue graphs, and automated PDF invoice generation.

#### 7.7 Pre-Order App for Canteen
- **Problem Solved:** Campus canteen congestion during peak hours resulting in delayed service and food waste.
- **Architecture:** React frontend built with Vite and Tailwind CSS; Firebase Firestore backend for zero-latency real-time order state updates. Rapid AI-assisted full-stack project.
- **Features:** Real-time digital menu, order scheduling, kitchen dashboard for order preparation states, and sales tracking.

---

## 8. Verification & Accuracy Notes
- Dates and employment records strictly match verified documentation (Feb 2025 – Present for Kelvin6K; May 2025 – Jun 2026 for Speedzy; 2022 – 2026 for B.Tech ECE at Crescent).
- Pre-college/earlier hardware builds have no invented dates and are presented honestly.
- Technical skills reflect true hands-on experience on physical machines, distinguishing professional usage from academic exploration.

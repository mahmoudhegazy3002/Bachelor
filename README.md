# Compact 3-DOF Spherical Wrist for 7-DOF Robotic Arm

## Overview
This repository details the mechanical design, motor selection, and fabrication of a 3-Degree-of-Freedom (3-DOF) spherical robotic wrist. Developed as part of a Mechatronics Bachelor's project at the German University in Cairo (GUC), this wrist serves as an integrated, structural sub-system within a larger, team-built 7-DOF robotic arm manipulator, providing the critical pitch, roll, and yaw movements. 

My specific responsibility within the team was the end-to-end realization of this 3-DOF wrist section. The primary engineering constraint was **miniaturization**—designing the wrist to be as compact as possible to minimize weight and inertia at the end of the arm, while maintaining structural integrity and sufficient payload capacity.

## Key Engineering Contributions

### 1. Mechanical Design & Miniaturization
* **Software:** SolidWorks
* **Description:** Engineered a spherical wrist mechanism where the axes of the final three joints perfectly intersect. The CAD process focused heavily on structural integration with the preceding arm links, reducing the overall footprint, and optimizing internal geometry to achieve the smallest possible volume without compromising the arm's continuous kinematic chain.

### 2. Motor Sizing & Selection
* **Description:** Conducted torque, speed, and dynamic load calculations to select the appropriate stepper motors. The challenge was finding actuators that fit within the strict physical boundaries of the miniaturized wrist while delivering the necessary holding torque and precision for the arm's overall payload.

### 3. Fabrication & Assembly
* **Manufacturing:** FDM 3D Printing and hardware assembly.
* **Description:** Transitioned the CAD models into physical reality. This involved designing for manufacturability (DFM) using FDM technology, managing tight tolerances for the internal moving parts, and fully assembling the 3-DOF structural segment to ensure smooth mechanical transmission.

## Repository Structure
* `/cad`: SolidWorks part and assembly files (`.SLDPRT`, `.SLDASM`) for the highly compact 3-DOF wrist segment.
* `/calculations`: Engineering calculations and datasheets justifying the stepper motor selection and torque requirements.
* `/fabrication`: Ready-to-print `.STL` files, optimal slicing parameters for FDM, and the complete Bill of Materials (BOM).
* `/docs`: Project documentation, design iterations, and the final thesis section detailing the wrist's development.

## System Integration
This 3-DOF wrist was designed specifically to mate with the preceding arm segments developed by the project team. The physical mounting interfaces, joint alignments, and motor wiring paths were engineered to support the main structure and the team's overarching CODESYS PLC control architecture.

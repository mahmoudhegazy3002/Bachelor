# Compact 3-DOF Spherical Wrist for Industrial 7-DOF Robotic Arm

## Overview
This repository details the mechanical design, motor selection, and manufacturing files for a 3-Degree-of-Freedom (3-DOF) spherical robotic wrist. Developed as part of a Mechatronics Bachelor's project at the German University in Cairo (GUC), this wrist serves as an integrated, load-bearing sub-system within a larger, team-built 7-DOF metal robotic arm manipulator, providing the critical pitch, roll, and yaw movements. 

My specific responsibility within the team was the end-to-end realization of this 3-DOF wrist section. The primary engineering constraint was **miniaturization**—designing the wrist to be as compact as possible to minimize the moment of inertia at the end of the metal arm, while maintaining the structural rigidity required for industrial payloads.

## Key Engineering Contributions

### 1. Mechanical Design & Miniaturization
* **Software:** SolidWorks
* **Description:** Engineered a spherical wrist mechanism where the axes of the final three joints perfectly intersect. The CAD process focused heavily on structural integration with the preceding metal arm links, reducing the overall footprint, and optimizing the internal geometry to achieve the smallest possible volume without compromising the arm's continuous kinematic chain or payload capacity.

### 2. Motor Sizing & Selection
* **Description:** Conducted torque, speed, and dynamic load calculations to select the appropriate stepper motors. The challenge was sourcing actuators that fit within the strict physical boundaries of the miniaturized wrist while delivering the necessary holding torque to handle the weight of the fabricated metal components and the external payload.

### 3. Industrial Fabrication & Assembly
* **Manufacturing:** CNC Machining and Metal Fabrication.
* **Description:** Transitioned the CAD models into manufacturing-ready formats. This involved strict Design for Manufacturability (DFM) principles for metalworking, managing tight machining tolerances for the internal moving parts, and ensuring precise assembly of the 3-DOF structural segment for smooth mechanical transmission.

## Repository Structure
* `/cad`: Native SolidWorks part and assembly files (`.SLDPRT`, `.SLDASM`) detailing the full 3-DOF wrist mechanism.
* `/manufacturing`: Universal `.STEP` files for CAM software, and `.DXF` profiles for laser cutting or 2D machining operations.
* `/calculations`: Engineering calculations and datasheets justifying the stepper motor selection and dynamic torque requirements.
* `/docs`: Project documentation, design iterations, engineering drawings, and the final thesis section detailing the wrist's development.

## System Integration
This 3-DOF wrist was engineered specifically to mate with the preceding fabricated arm segments developed by the project team. The physical mounting interfaces, joint alignments, and motor wiring paths were designed to support the main heavy-duty structure and the team's overarching CODESYS PLC control architecture.

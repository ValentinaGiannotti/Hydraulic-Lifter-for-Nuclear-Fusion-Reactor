# Virtual Prototyping of Hydraulic-Lifter-for-Nuclear-Fusion-Reactor 

## Table of Contents
1. [Introduction](#introduction)
2. [Functional Requirements](#functional-requirements)
3. [Modeling](#modeling)
   - [2D and 3D Implementation](#2d-and-3d-implementation)
   - [System Components](#system-components)
4. [Analysis](#analysis)
   - [Structural Analysis](#structural-analysis)
   - [Kinematic Analysis](#kinematic-analysis)
   - [Ergonomic Analysis](#ergonomic-analysis)
6. [Authors](#authors)

## Introduction
This project focuses on the **Virtual Prototyping** of an auxiliary equipment system for installing **Plasma Facing Components** in a **Remote Handling (RH) facility** for a nuclear fusion reactor. The main objective is to design a **mechanical/mechatronic system** that supports operators during the assembly, disassembly, and handling of specific components.

The system must:
- Ensure safe and easy access for operators.
- Guarantee precise transport and positioning of **First Wall** modules.
- Enable unobstructed visual inspections.

## Functional Requirements
1. Allow the operator to **ergonomically** reach First Wall modules for manual assembly/disassembly.
2. Ensure the **proper gripping** of **Outboard and Inboard First Wall** modules.
3. Have **sufficient degrees of freedom** to position modules in all test scenarios.
4. Be **structurally robust** to transport modules weighing up to **250 kg**.
5. Enable **visual inspection** of First Wall and Divertor mockups.
6. Be designed to **ensure worker safety** during use.
7. Prevent damage to the **First Wall modules** and other system components.
8. Support **ergonomic operation** (simulated with **JACK**).
9. Allow the operator to always have easy access to work tools.

## Modeling
### 2D and 3D Implementation
2D and 3D models were developed to study the system's structure and functionality. The main implemented solutions include:
- **Rail system** with circular guidance and internal supports.
- **Lifting trolley** with lifting columns and platform.
- **Manipulator with vacuum system** for module positioning.

### System Components
- **Rail:** Enables movement along a predefined trajectory.
- **Lifting trolley:** Adjusts the operator’s vertical position.
- **Manipulator with vacuum system:** Facilitates the grasping and handling of First Wall modules.

## Analysis
### Structural Analysis
- **FEM simulations** with a **tetrahedral mesh** (10 mm) to assess system strength.
- Identification of **maximum stress points** to verify structural robustness.

### Kinematic Analysis
- Study of the **rail mechanism** (translational joint along a circular path).
- Simulation of the **lifting trolley** (vertical prismatic joint).
- Verification of the **manipulator** (combination of revolute and prismatic joints).

### Ergonomic Analysis
- **JACK simulations** to evaluate operator ergonomics.
- Tests in **various operational positions** (horizontal, upper, lower).

## Authors
- **Valentina Giannotti** 
- **Andrea Morghen** 
- **Ludovica Ruggiero**

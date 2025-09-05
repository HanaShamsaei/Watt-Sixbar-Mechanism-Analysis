# Watt Six-Bar Mechanism Analysis

This repository contains the **kinematic and dynamic analysis of a Watt six-bar mechanism** as part of the *Machine Dynamics (دینامیک ماشین)* course project at the University of Tehran.

The project implements both **analytical modeling** and **simulation-based verification** using **MATLAB, SAM, and Adams/View**. Results are validated across multiple tools, and an animation of the mechanism’s motion is included.

---

## Project Objectives
- Model and simulate a Watt six-bar mechanism.  
- Perform **kinematic analysis**:  
  - Position (angles, displacements)  
  - Velocity (angular velocities)  
  - Acceleration (angular accelerations)  
- Perform **dynamic analysis**:  
  - Forces at joints  
  - Required input torque  
  - Reaction forces at links  
- Compare results obtained from:
  - MATLAB (analytical loop-closure & force equations)  
  - SAM (educational mechanism analysis software)  
  - Adams/View (professional multibody dynamics software)  

---

## Tools & Methods
- **MATLAB**:  
  - Loop-closure equations  
  - Position, velocity, and acceleration analysis  
  - Dynamic equations of motion for links  
  - Free body diagrams and force/torque calculations  
  - Mechanism animation generated frame-by-frame  

- **SAM**:  
  - Kinematic simulation  
  - Position, velocity, and acceleration plots  

- **Adams/View**:  
  - Full kinematic and dynamic simulation  
  - Force and torque evaluations at joints  
  - Numerical comparison with MATLAB results  

---

## Results
- Position, velocity, and acceleration curves for all links.  
- Joint forces (C, D, H) and input torque variation over time.  
- Comparison between MATLAB, SAM, and Adams/View shows close agreement.  
- Differences are analyzed (e.g., modeling assumptions, inertia definition, solver differences).  

---

## Project Video
The repository includes an **animation video** of the six-bar mechanism motion and simulation results:  

**File:** `SP1_810600097.mp4`  

This video demonstrates the MATLAB-generated animation and simulation output.  

---

## 📂 Repository Structure

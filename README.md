# Simulation-of-Two-Robots-Sharing-a-Workspace-Using-MATLAB


This repository contains the MATLAB code and simulation for a project that demonstrates the coordination of two robots (an industrial robotic arm and a mobile robot) sharing a workspace. The project focuses on motion planning, collision avoidance, and task synchronization between the two robots.

## Project Overview

The project simulates a scenario where an industrial robotic arm and a mobile robot collaborate to perform a pick-and-place task in a shared workspace. The industrial robot picks up a workpiece and places it on the mobile robot, which then transports the workpiece to a designated storage area. The simulation ensures that both robots operate without collisions and coordinate their actions efficiently.

### Key Features:
- **Industrial Robot (6-DOF Robotic Arm):** 
  - Performs pick-and-place tasks using inverse kinematics for precise motion control.
  - Utilizes trajectory planning to generate smooth paths for the end-effector.
  
- **Mobile Robot (Differential-Drive Robot):**
  - Navigates the workspace using path planning algorithms.
  - Transports the workpiece from the pickup location to the storage area.
  
- **Coordination Mechanism:**
  - The robots communicate via a central control system to synchronize their actions.
  - Event-based signals ensure that tasks are performed in the correct sequence.

## Repository Structure

- **`/code`**: Contains MATLAB scripts and Simulink models for simulating the robots.
  - `industrial_robot.m`: Script for controlling the 6-DOF robotic arm.
  - `mobile_robot.m`: Script for controlling the differential-drive mobile robot.
  - `simulation_main.m`: Main script to run the simulation and visualize the results.
  
- **`/docs`**: Contains documentation related to the project, including the project report and references.

- **`/models`**: Contains CAD models of the robots (e.g., Kuka KR-16) used in the simulation.

- **`/results`**: Contains simulation results, including plots and animations of the robots' movements.

## Requirements

To run the simulation, you will need:
- MATLAB (version R2020a or later)
- MATLAB Robotics Toolbox
- MATLAB Mobile Robot Toolbox
- Simulink (optional, for control system modeling)

## How to Run the Simulation

1. Clone the repository:
   ```bash
   git clone https://github.com/edwardtimasare/Simulation-of-Two-Robots-Sharing-a-Workspace-Using-MATLAB.git

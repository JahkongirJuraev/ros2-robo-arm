# ROS 2 Robotic Arm (Robo-Arm)

This repository contains a ROS 2 workspace for simulating and controlling a simple robotic arm (“Robo-Arm”) using URDF/Xacro, Gazebo, ros2_control and MoveIt.  
It was created as a learning and experimentation project for robot modelling, simulation and motion control.

---

## Overview

The project focuses on:

- Building a **ROS 2 workspace** for a robotic arm (`arduinobot_ws`)
- Modelling the arm with **URDF/Xacro**
- Running the robot in **Gazebo** simulation
- Configuring **ros2_control** controllers for joint-space motion
- Integrating with **MoveIt** for motion planning (planning scene, groups, trajectories)
- Providing launch files to quickly bring up the full stack

This makes the repository a small but complete example of a ROS 2 manipulation setup, useful for learning and experimentation.

---

## Repository Structure

```text
ros2-robo-arm/
├── arduinobot_ws/        # ROS 2 workspace
│   ├── src/              # Robot description, control, MoveIt and bringup packages
│   ├── install/          # Populated after building (colcon)
│   ├── build/            # Build artifacts
│   └── log/              # Logs from colcon/ROS 2 runs
└── .gitignore

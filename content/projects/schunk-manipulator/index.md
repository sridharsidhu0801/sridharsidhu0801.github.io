---
title: "Manipulator Modeling, Control, and ROS Integration"
date: 2021-01-01
lastmod: 2026-10-08
summary: "Manipulator engineering from nonlinear modeling and state-space control to MoveIt motion planning, Gazebo simulation, and SCHUNK LWA4D hardware integration."
tags: [Control Systems, Robotics, Hardware, Engineering Project]
tech_stack: [ROS, ROS-Industrial, MoveIt, Gazebo, C++, MATLAB, Simulink]
featured: true
status: "Platform integration and control studies"
role: "Robotics and controls developer"
highlights:
  - "Seven-DOF SCHUNK LWA4D modeling and integration"
  - "MoveIt planning, Gazebo simulation, and ROS control"
  - "Two-link robot state feedback, observers, and tracking"
---

This project brings together two connected layers of manipulator engineering: platform integration for the seven-degree-of-freedom SCHUNK LWA4D and advanced-control studies using a nonlinear two-link robot. The result is a progression from mathematical modeling and controller design to robot description, motion planning, simulation, and hardware-interface investigation.

The SCHUNK work covers ROS, ROS-Industrial, Gazebo, MoveIt, forward and inverse kinematics, joint-space trajectories, and CAN-USB integration. The coursework section is labeled separately so simulation studies are not presented as physical-arm experiments.

{{< manipulator-projects >}}

> **Evidence boundary:** Motion planning and trajectory execution are documented in simulation. The preserved hardware work demonstrates platform setup, PowerCube/CAN-USB evaluation, and communication troubleshooting; it does not establish completed ROS trajectory execution on the physical arm. Joystick teleoperation will be added after its original implementation evidence is located.

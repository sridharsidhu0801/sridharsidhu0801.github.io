---
title: "Manipulator Modeling, Control, and ROS Integration"
date: 2021-01-01
lastmod: 2026-10-09
summary: "Physical SCHUNK LWA4D joint-space PID control in ROS/C++, integrating Gazebo/MoveIt planning, hardware feedback, CAN communication, and manipulator control studies."
tags: [Control Systems, Robotics, Hardware, Engineering Project]
tech_stack: [ROS, ROS-Industrial, MoveIt, Gazebo, C++, MATLAB, Simulink]
featured: true
status: "Physical implementation and control studies"
role: "Robotics and controls developer"
highlights:
  - "Seven-DOF SCHUNK LWA4D modeling and integration"
  - "MoveIt planning, Gazebo simulation, and ROS control"
  - "Two-link robot state feedback, observers, and tracking"
---

I developed and implemented a closed-loop joint-space PID controller in C++ using ROS Melodic for the seven-degree-of-freedom SCHUNK LWA4D. The workflow connects Gazebo/MoveIt motion planning with real-time joint feedback and control of the physical manipulator. Related coursework develops the modeling, state-feedback, observer, and tracking foundations using a nonlinear two-link robot.

In MoveIt, interactive markers specify a desired end-effector pose and inverse kinematics produces target joint angles. My C++ controller receives these targets and actual hardware joint positions, computes joint errors, and sends corrective commands through the ROS hardware interface. The physical implementation achieved bidirectional communication, live joint-state feedback, and end-effector motion to desired poses.

{{< manipulator-projects >}}

### Resolving the hardware integration

When the manipulator initially failed to respond, I inspected ROS topics and messages and recorded joint-state feedback with rosbag. I traced the communication problem to a faulty or incompatible legacy CAN-USB interface and its drivers. Replacing it with an ESD CAN-USB interface restored communication. I then initialized the Schunk PowerCube actuator modules with the manufacturer's Windows software, enabling motion commands through ROS.

Joystick teleoperation is part of the platform work; its original media and configuration will be added as the project documentation expands. The two-link control studies below are coursework simulations.

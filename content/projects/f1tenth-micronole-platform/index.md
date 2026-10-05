---
title: "F1TENTH / MicroNole Autonomous Vehicle Platform"
date: 2026-09-10
summary: "Reusable vehicle-platform engineering for sensing, ROS integration, modeling, parameter estimation, and controlled multi-vehicle experiments."
tags: [Autonomous Vehicles, Robotics, Hardware, Engineering Project]
tech_stack: [F1TENTH, MicroNole, MATLAB, Simulink, ROS, LiDAR]
featured: true
status: "Platform integration under review"
role: "Controls and autonomy developer"
highlights:
  - "Vehicle modeling and parameter-estimation lineage"
  - "LiDAR, perception, and ROS platform resources"
  - "Reusable hardware base for networked-control experiments"
---

This engineering project separates reusable MicroNole/F1TENTH platform capabilities from paper-specific experiments. It brings together vehicle interfaces, modeling resources, perception and road-sign material, ROS components, Simulink models, and hardware media.

The platform supports the broader workflow used across my research: establish a trustworthy vehicle model, integrate sensing and middleware, test bounded behaviors, and then reuse the same hardware foundation for teleoperation and multi-agent control.

I built the vehicle platform from individual mechanical, electrical, computing, and sensing components. The build required chassis and drivetrain assembly, power and motor-controller wiring, steering and suspension checks, NVIDIA Jetson integration, LiDAR and depth-camera preparation, and custom sensor-mount development.

{{< f1tenth-hardware-build >}}

## Platform capabilities

This hardware base supports the next project modules that will be documented here, including YOLO-based speed- and stop-sign detection, lane following, and PID, LQR, and Stanley steering controllers.

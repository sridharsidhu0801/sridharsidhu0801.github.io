---
title: "F1TENTH / MicroNole Autonomous Vehicle Platform"
date: 2026-09-10
lastmod: 2026-10-09
summary: "Platform engineering from hardware assembly and vehicle modeling through ROS sensing, perception, lane following, and steering control."
tags: [Autonomous Vehicles, Robotics, Hardware, Engineering Project]
tech_stack: [F1TENTH, MicroNole, C++, ROS, NVIDIA Jetson, YOLO, MATLAB, Simulink, Speedgoat, LiDAR]
featured: true
status: "Active research platform · 4 years of use"
role: "Controls and autonomy developer"
highlights:
  - "Built and integrated the F1TENTH vehicle from individual components"
  - "Vehicle modeling, parameter estimation, ROS, and sensor integration"
  - "Traffic-sign perception, lane following, and steering-control development"
---

This engineering project separates reusable MicroNole/F1TENTH platform capabilities from paper-specific experiments. It brings together vehicle interfaces, modeling resources, perception and road-sign material, ROS components, Simulink models, and hardware media.

The platform supports a complete autonomy workflow: establish a trustworthy vehicle model, integrate sensing and middleware, develop perception and planning capabilities, and implement closed-loop vehicle control.

I built the vehicle platform from individual mechanical, electrical, computing, and sensing components. The build required chassis and drivetrain assembly, power and motor-controller wiring, steering and suspension checks, NVIDIA Jetson integration, LiDAR and depth-camera preparation, and custom sensor-mount development.

Over four years of sustained physical-platform use, my primary responsibility has been control-system development and experimental validation. I maintain ROS/C++ control implementations, tune controllers, run hardware experiments, troubleshoot integration issues, and validate research algorithms.

{{< f1tenth-platform-projects >}}

### Research deployments

**Teleoperation under communication delay:** I implemented racing-cockpit teleoperation under significant communication delays, contributing to a paper published at the American Control Conference. See [vehicle teleoperation](/projects/teleoperation-wave-variables/).

**Physical and real-time virtual platoons:** I developed CACC experiments combining three physical F1TENTH vehicles with additional Simulink agents running on a Speedgoat real-time target. The experiments evaluate velocity consensus, intervehicle spacing, and string stability and contributed to a journal submission under review. I continue using the platform to investigate generalized vehicle communication topologies.

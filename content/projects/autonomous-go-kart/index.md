---
title: "Autonomous Go-Kart — Modeling, DBW, and SBW"
date: 2025-01-01
lastmod: 2026-10-09
summary: "ROS 2 vehicle control on Jetson Orin Nano: embedded steering PID, PI cruise control, vehicle modeling, safety watchdogs, and a torque-driven steering redesign."
tags: [Control Systems, Robotics, Hardware]
tech_stack: [MATLAB, Simulink, NMPC, ROS 2, NVIDIA Jetson, Arduino]
featured: true
status: "Engineering platform"
role: "Controls and integration engineer"
highlights:
  - "Nonlinear vehicle model and NMPC workflow"
  - "Embedded steering PID and longitudinal PI cruise control"
  - "Command watchdog, steering calibration, and mechanical torque redesign"
---

I integrated a ROS 2 control architecture running on an NVIDIA Jetson Orin Nano with the drive-by-wire and steer-by-wire systems of a full-size experimental go-kart. My ownership covered control logic, vehicle dynamics modeling, embedded steering control, longitudinal cruise control, and integration with the steering and propulsion hardware.

The project connects MATLAB/Simulink controller development with physical testing, feedback timing, actuator initialization, and mechanical reliability. The modules below describe the engineering work and the problems resolved during testing.

{{< gokart-control-projects >}}


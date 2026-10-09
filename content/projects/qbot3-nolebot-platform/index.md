---
title: "QBot3 / NoleBot Mobile Robotics Platform"
date: 2026-09-09
lastmod: 2026-10-09
summary: "Single-robot engineering across DDWMR modeling, path tracking, SLAM, autonomous navigation, and teleoperation."
tags: [Robotics, Hardware, Engineering Project, Autonomous Vehicles]
tech_stack: [QBot3, ROS, C++, RViz, MATLAB, Simulink, Python]
featured: true
status: "Active research platform · 5 years of use"
role: "Primary developer and operator"
highlights:
  - "Straight-line, circular, and figure-eight path tracking"
  - "DDWMR modeling and controller-development foundation"
  - "SLAM, navigation, obstacle avoidance, and teleoperation"
---

The NoleBot/QBot3 platform project collects the reusable engineering work developed and tested with one differential-drive mobile robot. It connects mathematical modeling and motion control with ROS-based mapping, navigation, and hands-on operation of the physical platform.

The main image shows the physical robot and its onboard computing, power, and sensing integration. The project modules below separate the major single-robot capabilities so their simulation results, plots, photographs, and short experiment videos can be added as the media is reviewed.

I have used and maintained the physical QBot platform for five years, with responsibility for ROS/C++ implementations, controller tuning, hardware experiments, troubleshooting, and experimental analysis. I implemented and experimentally validated path tracking under false-data-injection attacks, contributing to a publication in *Control Engineering Practice*.

{{< nolebot-single-robot-projects >}}

### From single-robot capabilities to cooperative experiments

I also developed multi-QBot formation-control experiments under communication delays, contributing to a journal paper under review. The single-robot capabilities above support this work; coordinated experiments are presented in the [cooperative vehicle-following project](/projects/ddwmr-cacc/).

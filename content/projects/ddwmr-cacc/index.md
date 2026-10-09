---
title: "DDWMR Navigation and Cooperative Vehicle Following"
date: 2025-06-01
summary: "Navigation, parameter estimation, path tracking, and cooperative adaptive cruise control for differential-drive mobile robots."
tags: [Control Systems, Multi-Agent Systems, Robotics, Hardware]
tech_stack: [MATLAB, Simulink, ROS, Gazebo, Python, C++]
featured: true
status: "Experimental lineage under review"
role: "Controls and robotics developer"
highlights:
  - "SLAM, go-to-goal navigation, and obstacle avoidance"
  - "Path tracking with parameter estimation"
  - "CACC and string-stability experiments"
---

This body of work uses differential-drive robots as a bridge between mobile-robot autonomy and networked vehicle control. It covers mapping and navigation, trajectory tracking, model parameter estimation, and cooperative longitudinal behavior.

### Distributed control on physical robots

I developed C++ ROS nodes that receive neighboring robot states, compute local commands for consensus or formation objectives, and execute those commands on the robot. I configured launch files to coordinate the nodes required for multi-robot experiments across QBot, TurtleBot, and F1TENTH platforms.

My experimental work includes multi-QBot formation control under communication delays and cooperative vehicle-following studies. I use MATLAB to analyze ROS bag data and generate experimental comparisons and publication figures.

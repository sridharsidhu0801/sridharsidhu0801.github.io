---
title: "Passive Vehicle Teleoperation Under Delay"
date: 2024-07-10
summary: "Wave-variable passivity and predictor-based control for stable human-in-the-loop F1TENTH teleoperation with communication delay."
tags: [Control Systems, Robotics, Hardware, Teleoperation]
tech_stack: [MATLAB, Simulink, ROS, F1TENTH, NVIDIA Jetson]
featured: true
status: "Published — ACC 2024"
role: "Researcher and controls developer"
highlights:
  - "Passivity-oriented wave-variable communication"
  - "Smith and minimum-jerk predictor comparisons"
  - "Offline reproduction plus hardware-oriented Simulink models"
---

This work addresses bilateral vehicle teleoperation when network delay can destabilize the interaction between a human operator and a remote vehicle. The architecture combines wave variables with predictor techniques and separates four comparison cases: no delay, delayed operation, passive communication, and passive communication with prediction.

## Engineering contribution

- Developed the MATLAB/Simulink control and comparison workflow.
- Integrated the research models with an F1TENTH-oriented ROS toolchain.
- Preserved a separate offline model for safe reproduction without starting ROS or connecting hardware.
- Connected the research repository to the companion hardware-launch and ROS-node repository.

The resulting work was published at the 2024 American Control Conference.

[View the public repository](https://github.com/sridharsidhu0801/teleop-wv-under-delay) · [Read the ACC 2024 paper](https://ieeexplore.ieee.org/document/10644849)

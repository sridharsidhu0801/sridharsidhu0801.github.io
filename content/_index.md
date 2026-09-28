---
title: ''
summary: 'Controls and robotics engineering portfolio of Sridhar Babu Mudhangulla'
date: 2026-09-23
type: landing

sections:
  - block: portfolio-hero
    id: hero
    content:
      username: me

  - block: portfolio
    id: projects
    content:
      title: "Control, Robotics & Autonomous Systems"
      subtitle: "Selected hardware platforms, engineering projects, and research programs—from modeling to physical validation"
      count: 0
      filters:
        folders: [projects]
      buttons:
        - name: All
          tag: '*'
        - name: Engineering Projects
          tag: Engineering Project
        - name: Autonomous Vehicles
          tag: Autonomous Vehicles
        - name: Control Systems
          tag: Control Systems
        - name: Multi-Agent Systems
          tag: Multi-Agent Systems
        - name: Robotics
          tag: Robotics
        - name: Hardware
          tag: Hardware
      default_button_index: 0
    design:
      columns: 3
      background:
        color:
          light: "#ffffff"
          dark: "#0b1622"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: hardware-reel
    id: hardware-in-motion

  - block: tech-stack
    id: skills
    content:
      title: "Engineering Toolkit"
      subtitle: "Methods and platforms used across modeling, verification, and implementation"
      categories:
        - name: Control & Estimation
          items:
            - {name: Model Predictive Control, icon: hero/cpu-chip}
            - {name: Robust & LMI Methods, icon: hero/shield-check}
            - {name: PID / LQR, icon: hero/adjustments-horizontal}
            - {name: Kalman Filtering, icon: hero/chart-bar-square}
        - name: Robotics & Autonomy
          items:
            - {name: ROS / ROS 2, icon: devicon/ros}
            - {name: Multi-Agent Systems, icon: hero/share}
            - {name: Motion Planning, icon: hero/map}
            - {name: SLAM & Navigation, icon: hero/map-pin}
        - name: Modeling & Software
          items:
            - {name: MATLAB / Simulink, icon: devicon/matlab}
            - {name: Python, icon: devicon/python}
            - {name: C / C++, icon: devicon/cplusplus}
            - {name: Git, icon: devicon/git}
        - name: Platforms
          items:
            - {name: NVIDIA Jetson, icon: hero/cpu-chip}
            - {name: F1TENTH, icon: hero/truck}
            - {name: TurtleBot / QBot, icon: hero/cog-6-tooth}
            - {name: SCHUNK LWA4D, icon: hero/wrench-screwdriver}
    design:
      style: grid
      show_levels: false
      background:
        color:
          light: "#eef4f8"
          dark: "#07111c"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: resume-experience
    id: experience
    content:
      username: me
    design:
      columns: '1'
      date_format: Jan 2006
      background:
        color:
          light: "#ffffff"
          dark: "#0b1622"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: markdown
    id: publications
    content:
      title: "Selected Publications"
      text: |-
        ### Generalized String-Stability Criteria for Consensus Protocols

        **Accepted — 23rd IFAC World Congress, 2026**  
        A unified frequency-domain framework showing how communication richness and consensus order shape disturbance propagation in leader–follower multi-agent systems.

        [Read the preprint on arXiv](https://arxiv.org/abs/2604.21329)

        ---

        ### Enhancing Consensus and Stability in Teleoperated Multi-Agent Systems Under Large Communication Delays

        **Presented — Modeling, Estimation and Control Conference, 2025; manuscript under major revision**  
        Extends wave-variable passivity concepts to teleoperated leader–follower multi-agent systems and validates delay robustness using differential-drive mobile robots.

        [View the research record](https://doi.org/10.2139/ssrn.6749840)

        ---

        ### Passive Stability and Adaptive Control of Teleoperated System using Wave Variables and Predictor Techniques

        **Published — American Control Conference, 2024**  
        A human-in-the-loop vehicle teleoperation framework combining passive wave-variable communication with predictor techniques to manage delayed bilateral interaction.

        [Read the paper on IEEE Xplore](https://ieeexplore.ieee.org/document/10644849) · [Explore the public research repository](https://github.com/sridharsidhu0801/teleop-wv-under-delay)

        ---

        ### Moving-Horizon False Data Injection Attack Design against Cyber–Physical Systems

        **Published — Control Engineering Practice, 2023**  
        Develops a recursively feasible moving-horizon attack framework and validates it through an IEEE 14-bus simulation and a wheeled-mobile-robot path-tracking experiment.

        [Read the journal article](https://doi.org/10.1016/j.conengprac.2023.105552) · [View the open preprint](https://arxiv.org/abs/2304.11684)

        [View the complete Google Scholar profile](https://scholar.google.com/citations?hl=en&user=eJS_sekAAAAJ)
    design:
      columns: '1'
      background:
        color:
          light: "#eef4f8"
          dark: "#07111c"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: contact-info
    id: contact
    content:
      title: "Let's Connect"
      subtitle: "Controls, autonomy, robotics, and research collaboration"
      text: |-
        I am interested in controls and robotics roles where mathematical analysis, reliable software, and physical-system validation belong in the same engineering workflow.
      email: sm19ch@fsu.edu
      autolink: true
    design:
      columns: '1'
      background:
        color:
          light: "#ffffff"
          dark: "#0b1622"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

---

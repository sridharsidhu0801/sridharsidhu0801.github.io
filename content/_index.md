---
title: ''
summary: 'Controls and robotics engineering portfolio of Sridhar Babu Mudhangulla'
date: 2026-09-23
type: landing

sections:
  - block: dev-hero
    id: hero
    content:
      username: me
      greeting: "Hello, I'm"
      show_status: true
      show_scroll_indicator: true
      typewriter:
        enable: true
        prefix: "I engineer"
        strings:
          - "resilient multi-agent systems"
          - "networked control under delay"
          - "robot and vehicle autonomy"
          - "simulation-to-hardware workflows"
        type_speed: 60
        delete_speed: 35
        pause_time: 2400
      cta_buttons:
        - text: Explore My Work
          url: "#projects"
          icon: arrow-down
        - text: Contact Me
          url: "#contact"
          icon: envelope
    design:
      style: centered
      avatar_shape: circle
      animations: true
      background:
        color:
          light: "#f5f8fb"
          dark: "#07111c"
      spacing:
        padding: ["6rem", "0", "4rem", "0"]

  - block: portfolio
    id: projects
    content:
      title: "Research & Engineering"
      subtitle: "Control theory carried through simulation, middleware, and physical platforms"
      count: 0
      filters:
        folders: [projects]
      buttons:
        - name: All
          tag: '*'
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
      title: "Selected Publication"
      text: |-
        ### Passive Stability and Adaptive Control of Teleoperated System using Wave Variables and Predictor Techniques

        **American Control Conference, 2024**  
        A human-in-the-loop vehicle teleoperation framework combining passive wave-variable communication with predictor techniques to manage delayed bilateral interaction.

        [Read the paper on IEEE Xplore](https://ieeexplore.ieee.org/document/10644849) · [Explore the public research repository](https://github.com/sridharsidhu0801/teleop-wv-under-delay)

        Additional work on mesh stability, scalable consensus, robust formation control, and delayed multi-agent coordination is ongoing or under review and is described at an appropriate public level in the project case studies above.
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

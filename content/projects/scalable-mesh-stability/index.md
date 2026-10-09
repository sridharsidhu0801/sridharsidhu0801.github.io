---
title: "Scalable Mesh Stability Across Vehicle Platforms"
date: 2026-03-01
summary: "A cross-platform investigation of formation-error propagation and scalability using F1TENTH and NoleBot experiments."
tags: [Control Systems, Multi-Agent Systems, Hardware]
tech_stack: [MATLAB, Simulink, ROS, F1TENTH, NoleBot]
featured: true
status: "Research migration complete; scientific review ongoing"
role: "Researcher"
highlights:
  - "F1TENTH and NoleBot experiment tiers"
  - "ODE and network-scalability validation"
  - "Hardware evidence preserved with exact provenance"
---

This project studies how local vehicle interactions influence formation errors as the number of agents grows. It brings together theoretical notes, offline analyses, simulation models, and hardware experiment records without collapsing distinct platform implementations into one ambiguous runtime folder.

### Experimental implementation

I developed and maintained ROS/C++ control implementations and conducted controller tuning, hardware troubleshooting, and experimental validation. In the F1TENTH CACC experiments, three physical vehicles interact with additional real-time Simulink agents running on a Speedgoat target to evaluate velocity consensus, intervehicle spacing, and string stability.

The cooperative-platform work contributed to a journal submission under review. Ongoing experiments investigate generalized vehicle communication topologies. The preserved offline ODE and scalability workflows have also passed bounded reproduction tests; environment-dependent model reruns are tracked separately from the original hardware experiments.

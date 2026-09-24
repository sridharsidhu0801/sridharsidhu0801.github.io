---
title: "Mesh Stability on General Graph Topologies"
date: 2026-06-01
summary: "A two-tier research program studying mesh-stability criteria for higher-order multi-agent synchronization over undirected and directed graphs."
tags: [Control Systems, Multi-Agent Systems, Research]
tech_stack: [MATLAB, Simulink, LMI Methods, Graph Theory, H-infinity Analysis]
featured: true
status: "Under review / theory in development"
role: "Lead researcher"
highlights:
  - "Independent directed and undirected research tiers"
  - "Frequency-domain, direct, and LMI-based validation"
  - "Reproduced numerical workflows in clean disposable clones"
---

This project investigates when synchronization errors remain bounded across a formation as the communication graph and agent dynamics become more general. The repository deliberately separates the mature undirected study from the evolving directed-graph theory while sharing only genuinely common theory and utilities.

## Research workflow

- Define formation geometry and communication topology.
- Derive stability and induced-gain conditions for higher-order agents.
- Cross-check analytical bounds using direct numerical methods and LMI feasibility tests.
- Generate publication figures and numerical summary tables from repeatable experiment folders.

Both tiers have been rerun independently under MATLAB, while the directed theoretical development remains clearly labeled as ongoing.

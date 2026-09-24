# Sridhar Babu Mudhangulla — Controls & Robotics Portfolio

This repository contains the Hugo/HugoBlox source for Sridhar Babu Mudhangulla's controls and robotics engineering portfolio.

The site presents selected work in:

- robust, distributed, and networked control;
- multi-agent consensus, string stability, and mesh stability;
- delayed teleoperation and human-in-the-loop systems;
- autonomous vehicles, mobile robots, and robotic manipulators;
- MATLAB/Simulink, ROS/ROS 2, numerical optimization, and hardware-oriented experimentation.

## Portfolio structure

- `content/_index.md` — home page, expertise, experience, publication, and contact sections
- `content/projects/` — research and engineering case studies
- `data/authors/me.yaml` — author profile, education, interests, and technical skills
- `config/_default/` — site title, navigation, appearance, and repository settings
- `assets/` and project `featured.*` files — site and case-study visuals

## Local preview

Install the Hugo extended edition, then run:

```powershell
hugo server
```

Open the local address printed by Hugo. To build the production site:

```powershell
hugo --minify
```

## Content policy

The portfolio distinguishes published work, ongoing research, and engineering projects. Public repositories and publications are linked where available. Private or unpublished research is summarized without exposing restricted source files, manuscripts, or collaborator-owned material.

## Deployment

The intended public address is [sridharsidhu0801.github.io](https://sridharsidhu0801.github.io/). Review locally before publishing changes to GitHub Pages.

Built with the [HugoBlox Developer Portfolio template](https://github.com/HugoBlox/hugo-theme-developer-portfolio).

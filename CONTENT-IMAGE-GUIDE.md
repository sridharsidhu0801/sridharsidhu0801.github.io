# Portfolio Image and Video Replacement Guide

This file identifies the exact locations to update when assigning final images and hardware videos. Replacing media does not require changing the project text.

## Project-card images

Each project card automatically uses the `featured` image stored beside its `index.md`. Replace the listed file with the desired image while keeping the same filename and extension.

| Project | Image to replace |
|---|---|
| Autonomous go-kart | `content/projects/autonomous-go-kart/featured.jpg` |
| DDWMR navigation and CACC | `content/projects/ddwmr-cacc/featured.png` |
| F1TENTH / MicroNole platform | `content/projects/f1tenth-micronole-platform/featured.jpg` |
| General-graph mesh stability | `content/projects/general-graph-mesh-stability/featured.png` |
| Moving-horizon FDIA | `content/projects/moving-horizon-fdia/featured.jpg` |
| QBot3 / NoleBot platform | `content/projects/qbot3-nolebot-platform/featured.jpg` |
| Relative-position string stability | `content/projects/relative-position-string-stability/featured.png` |
| Robust formation control | `content/projects/robust-formation-control/featured.png` |
| Scalable mesh stability | `content/projects/scalable-mesh-stability/featured.png` |
| Scalable robust consensus | `content/projects/scalable-robust-consensus/featured.png` |
| SCHUNK manipulator | `content/projects/schunk-manipulator/featured.jpg` |
| Space-robot identification | `content/projects/space-robot-dynamics-identification/featured.jpg` |
| Teleoperation with wave variables | `content/projects/teleoperation-wave-variables/featured.jpg` |
| TurtleBot3 ROS 2 platform | `content/projects/turtlebot3-ros2-platform/featured.png` |

Recommended project-card image: landscape, 1600 × 900 pixels, JPG for photographs and PNG for diagrams. Keep the main hardware or plot near the center so responsive cropping does not remove it.

## Hero slideshow

The four slideshow assignments are defined in:

`layouts/_partials/hbx/blocks/portfolio-hero/block.html`

Current image files:

1. `static/media/hardware/teleoperation-cockpit-micronole.jpg`
2. `static/media/hardware/f1tenth-micronole-fleet.jpg`
3. `static/media/hardware/qbot-multi-agent-fleet.jpg`
4. `static/media/hardware/schunk-lwa4d-lab.jpg`

Replace a file in place to keep its existing caption. If an image represents a different experiment, also update the corresponding `portfolio-hero__caption-item` text in the hero block.

Recommended hero image: landscape, at least 1920 × 1080 pixels. Keep the most important subject in the center or right half because the name and introduction occupy the left side on desktop screens.

## Hardware in Motion

The section is defined in:

`layouts/_partials/hbx/blocks/hardware-reel/block.html`

Media locations:

- Videos: `static/media/reels/`
- Poster images: `static/media/hardware/`

Two cards are currently active. A reusable card template and four recommended future slots are included as comments directly below the active cards:

1. F1TENTH teleoperation under communication delay
2. TurtleBot3 robust formation control
3. Autonomous go-kart drive-by-wire / steer-by-wire
4. SCHUNK LWA4D trajectory tracking

For each slot, add an MP4 video, add a JPG poster, duplicate the template card, and replace its filenames, title, and one-sentence description. Use short muted clips, H.264 MP4, 16:9 aspect ratio, and preferably less than 8 MB per clip.


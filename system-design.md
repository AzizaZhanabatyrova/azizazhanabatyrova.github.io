# Robotics Pipeline Design

This page presents a high‑level architecture concept created as part of an interview case study.  
It outlines how sensing, perception, mapping, and planning modules interact to enable reliable robot operation.

<img src="assets/system_design.png" alt="System Design Diagram" width="400" style="float:right; margin:0 0 20px 20px;">

## Key Components
- **Sensing** → Cameras, IMU, and LiDAR provide raw data streams.
- **Perception** → SLAM and computer vision modules process sensor data for localization and scene understanding.
- **Mapping** → Builds a persistent 3D world representation for navigation.
- **Planning** → Generates safe trajectories based on the mapped environment.
- **Control** → Executes planned actions on robotic hardware.

## Design Choices
- Emphasized modularity so perception and mapping can evolve independently.
- Separated sensing from planning to support sim‑to‑real transfer.
- Highlighted robustness by layering localization and mapping.

## Takeaway
This case study demonstrates my ability to structure robotics systems at a conceptual level, balancing clarity, modularity, and robustness.

# A Sensor-Based Model Predictive Control Scheme for Safe Multi-Room Crowd Navigation

This repository contains videos and a demonstration website for research on wheeled robot navigation in crowded multi-room environments.

## Overview

This project presents a sensor-based Nonlinear Model Predictive Control (NMPC) framework for safe robot navigation in multi-room environments populated with static obstacles and moving humans. The approach leverages LiDAR and RGB-D data to provide accurate perception and Kalman Filters, regulated by Finite State Machines, for crowd state estimation.

## Key Features

- **High-level Planning**: Environment decomposition into convex navigable regions with graph-based path planning to reach goal positions
- **Motion Generation**: NMPC with Control Barrier Function (CBF) constraints for safe collision avoidance with both static and dynamic agents
- **Modular Architecture**: Integrated planning, perception, and control system adaptable to different platforms and sensor configurations
- **Real Platform**: Implemented and tested on the TIAGo mobile manipulator robot

## Contents

- `index.html` - Interactive demonstration website showcasing the research
- `videos/` - Simulation and experimental videos showing the robot navigating multi-room environments
- `images/` - Architecture diagrams and visual assets
- `script.js` - JavaScript for the demonstration website
- `styles.css` - Styling for the demonstration website

## Demonstrations

The repository includes:
- **Gazebo Simulations**: Videos of the TIAGo robot navigating various multi-room environments with static obstacles and moving humans
- **Real-world Experiments**: Clips of the actual robot traversing doors and avoiding humans in diverse dynamic environments
- **Full Project Video**: A comprehensive overview available on YouTube

## View the Project

Open `index.html` in a web browser to explore the interactive demonstration, or visit the [GitHub Pages site](https://gianni0907.github.io/crowd_navigation/) (if available).

## Authors

Giovanbattista Gravina, Francesco D'Orazio, Michele Cipriano, Tommaso Belvedere, Giuseppe Oriolo

Research conducted at the [DIAG Robotics Lab](https://www.diag.uniroma1.it/~labrob/), Sapienza University of Rome.

## License

© 2025 Giovanbattista Gravina - All rights reserved.

# Line Following Robot Challenge

## Overview

This project is part of the EMATM0053 Robotic Systems coursework at the University of Bristol, focusing on the development and programming of a Pololu 3Pi+ mobile robot to autonomously follow a predetermined line path. The challenge requires the robot to navigate through corners, curves, and intersections, autonomously determining the most efficient path back to the starting point. The codebase leverages the robot's onboard sensors and motor controllers to execute complex maneuvers, ensuring robust performance across various segments of the track. Below is a breakdown of the core functionalities:

## Features

### Autonomous Line Detection and Navigation

- Advanced Line Detection: Utilizes an array of integrated sensors to accurately detect lines under various lighting conditions and on different surfaces, enabling the robot to autonomously follow a predefined path.
- Dynamic Navigation: A state-based system intelligently navigates through complex paths, including corners, curves, and intersections, with high precision. This system dynamically adjusts to the robot's environment, ensuring smooth traversal over complex track configurations.

### Dynamic Navigation

The navigation logic is sophisticated, enabling the robot to identify and appropriately react to different elements of the track, including:

- Corners and Curves: The robot deciphers sharp angles and gradual bends, applying calculated adjustments to its speed and direction to smoothly navigate these sections.
- Intersections: Special handling is incorporated for challenging obstacles such as intersections, where the robot must choose the correct path.

### State-Based Decision Making

At the heart of the robot's operation is a state-based decision-making system. This system orchestrates the robot's behavior, transitioning between different modes of operation based on real-time sensor data. States include joining the line, following the line, turning, and handling special track features like crossroads.

### Codebase Design

- Modular Code Structure: The code is organized and well-commented, facilitating easy customization and further development. This modular approach allows for the efficient integration of additional features and improvements.

### Performance Optimization

- Customizable Thresholds and Settings: Allows for the adjustment of sensor sensitivity and motor output, ensuring optimized performance across a variety of tracks and conditions.
- Extensive Sensor Integration: A sophisticated sensor algorithm provides real-time feedback, enabling immediate adjustments to the robot's course, enhancing its responsiveness and accuracy in line following.

## Acknowledgments

- Special thanks to Dr. Paul O’Dowd and the University of Bristol's EMATM0053 Robotic Systems coursework team.
- Pololu Corporation for the 3Pi+ mobile robot and support materials.


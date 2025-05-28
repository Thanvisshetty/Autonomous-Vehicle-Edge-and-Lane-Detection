# Autonomous Vehicle Edge and Lane Detection

## Project Overview
The project presents a low-cost, real-time autonomous vehicle prototype that detects and follows lane markings using computer vision and IoT technologies, specifically without relying on expensive hardware like LiDAR or GPS.

## Objectives
Develop a system for real-time lane detection using a camera and image processing techniques.
Use an ESP32-CAM for video capture and an Arduino Uno R3 for motion control.
Employ a 4-wheel drive platform with mecanum wheels for omnidirectional movement.
Test the system under different lighting and surface conditions.

# Key Components & Methodology
Hardware: ESP32-CAM, Arduino Uno R3, 4WD base with mecanum wheels.
## Software Techniques:
1. Grayscale conversion

2. Gaussian blur

3. Canny edge detection

4. Region of Interest (ROI) selection

5. Hough Line Transform

## System Flow:
1. Capture video

2. Process frames

3. Detect lanes

4. Generate motion commands

5. Drive vehicle accordingly

# Findings & Contributions
1. Many current systems are either too expensive or computationally intensive.

2. The project offers a scalable, educational prototype using affordable and open-source tools.

3. Future enhancements may include obstacle detection, lane changing, and traffic sign recognition.

4. Aims to bridge the gap between robustness and affordability in autonomous vehicle systems.

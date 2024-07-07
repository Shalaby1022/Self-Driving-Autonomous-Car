## Project Overview

We are developing a self-driving autonomous car using advanced artificial intelligence techniques and machine learning algorithms, including neural network graphs and genetic algorithms. This project aims to simulate and implement autonomous driving capabilities in various stages and integrate both software and hardware components.

## Simulations

### Stage 1: Hardcoded JavaScript Simulation

- Implemented using FeedForward neural networks.
- Focuses on basic autonomous driving tasks.

### Stage 2: Unity C# for 2D Simulation

- Utilizes Unity game engine for more realistic 2D simulations.
- Enhances simulation complexity and visual fidelity.

### Stage 3: Carla for 3D Simulation

- Uses Carla simulator with Convolutional Neural Networks (CNN) and image processing.
- Mimics real-life scenarios with capabilities such as pedestrian detection, lane detection, and traffic sign recognition.
- Provides a platform for testing complex driving scenarios.

## Hardware Prototype

We have also developed a hardware prototype using Arduino C, servo motors, ultrasonic sensors, and a Bluetooth module (HC-05). The prototype features:

- **Obstacle Avoidance**: 
  - **Functionality**: Autonomous navigation around obstacles using ultrasonic sensors to measure distances and make decisions.
  - **Details**: The car measures distances to obstacles and navigates around them autonomously. If an obstacle is detected within a certain range, the car stops and decides the best direction to avoid it.
  
- **Bluetooth Control**: 
  - **Functionality**: Manual control of the car via Bluetooth for testing and development purposes.
  - **Details**: Allows manual control of the car using Bluetooth commands (e.g., forward, backward, left, right, stop). This feature is especially useful during the testing and development phases.

- **Voice Control**: 
  - **Functionality**: Voice commands to control the car's movements.
  - **Details**: Enables control of the car using voice commands. The car responds to commands for moving forward, backward, left, right, and stopping.
  
- **Ultrasonic Sensing**: 
  - **Functionality**: Measures distances to obstacles and adjusts movements accordingly.
  - **Details**: Uses an ultrasonic sensor to measure distances to obstacles. The sensor helps in determining the best path when an obstacle is detected on either side of the car.

## Presentation

For an overview and detailed explanation of our project, please refer to our presentation:

- [Autonomy Mobility Fusion Presentation](https://drive.google.com/file/u/4/d/1Lekqfe0vgKUBpHBO0uA8bYuV-UjQzoSc/view?usp=drive_web)

The presentation includes run and test case videos for each simulation and the hardware prototype, demonstrating the functionality and performance of our autonomous car in various scenarios.


## Conclusion

![Car Image](https://github.com/Shalaby1022/Self-Driving-Autonomous-Car/raw/master/Conclusion!)

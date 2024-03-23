# LiDARNavigatorBot

## Abstract
The LiDARNavigatorBot, also known as Alex is an innovative robotics project developed as a part of our Computer Engineering curriculum. This robot, Alex, is designed for a simulated search and rescue operation, capable of mapping environments using LiDAR and identifying victims through color sensing, all within a specified time frame. Detailed insights into Alex's functionality are available in the [LiDARNavigatorBot.pdf](https://github.com/ymirmeddeb/LiDARNavigatorBot/blob/main/docs/LiDARNavigatorBot_report.pdf).

## Introduction
Tasked with creating a robot that could navigate and perform tasks in a simulated search and rescue environment, our team engineered Alex to identify victims represented by colored targets, avoid obstacles, and operate remotely via teleoperation. This project required a blend of hardware integration, software development, and innovative problem-solving.

## Hardware
Key components that constitute Alex include:
- **Mainboard:** Arduino Uno for control operations.
- **Motors:** 2x DC Motors, facilitating movement.
- **Sensors:** Ultrasonic for distance measurement, a line-following sensor for navigation, and a color sensor for victim identification.
- **LiDAR:** Mounted atop for environmental mapping.
- **Power Supply:** 6V battery pack.

## Software
The brain of Alex is driven by software written in C++ for Arduino, emphasizing obstacle detection, victim identification, and efficient navigation. The source code is accessible in the `code` directory within this repository.

## Algorithm Overview
Alex's operational logic is straightforward yet sophisticated, encompassing:
- Autonomous forward movement until encountering an obstacle.
- Utilization of the color sensor to identify victims upon detection.
- Engaging decision-making protocols based on sensor readings for navigation.

## Challenges & Solutions
Our journey was marked by hurdles such as sensor noise and inconsistencies in motor power, which we overcame through rigorous calibration and the integration of software filters, significantly boosting Alex's operational efficiency.

## Conclusion
Successfully meeting our objectives, "Alex to the Rescue" demonstrated the practical application of our theoretical knowledge, underscoring our robot's ability to navigate and execute search and rescue missions autonomously.

## Acknowledgements
Special thanks to our project supervisor and the NUS College of Design and Engineering for providing resources and support.

## Pictures of the robot

![Picture 1](https://github.com/ymirmeddeb/LiDARNavigatorBot/assets/74667654/fb19e97d-6691-41cf-9a31-727cfc574f39)

![Picture 2](https://github.com/ymirmeddeb/LiDARNavigatorBot/assets/74667654/f15691fb-49d2-412e-8e71-8f083b55d95a)

![Picture 3](https://github.com/ymirmeddeb/LiDARNavigatorBot/assets/74667654/2c1a56ca-1bea-4c2b-b7e8-a7b1ff488765)

![Picture 4](https://github.com/ymirmeddeb/LiDARNavigatorBot/assets/74667654/8501ae0e-edfb-4ac4-9f5f-a76d713597aa)

![Picture 5](https://github.com/ymirmeddeb/LiDARNavigatorBot/assets/74667654/6edb6251-0e78-4cac-aee3-a3d12aeea7e8)



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
The brain of Alex is driven by software written in C++ for Arduino, emphasizing obstacle detection, victim identification, and efficient navigation. The source code is accessible in the `Mbot_Code.ino` within this repository.

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
We extend our gratitude to our project supervisor and the faculty at the National University of Singapore's College of Design and Engineering for their unwavering support and resources.

For a step-by-step guide on setting up and more details, please refer to the Wiki section of this repository.

## Contribution Guidelines
Contributions to the "Alex to the Rescue" project are highly encouraged! If you have any suggestions or improvements, please feel free to open an issue or submit a pull request.

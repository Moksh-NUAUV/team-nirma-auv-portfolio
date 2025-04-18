This project forms the backbone of Team Nirma AUV’s autonomy system. Built entirely in Python using ROS 2 Humble, the stack enables seamless communication between the main processor (Intel NUC) and the controller (Teensy 4.1).

Key features include:

Modular node-based architecture for control, perception, and mission execution.

Real-time data handling from sensors like IMU and depth sensors.

Serial and UDP communication bridges between the ROS 2 system and the embedded controller.

Support for both autonomous and manual override modes.

Smooth integration with OpenCV for vision and PyQt for GUI-based feedback display.

This stack powered our vehicle to a 2nd place finish at SAUVC 2025, showcasing its robustness in real-world competition scenarios.

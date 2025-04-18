### [📦 ROS 2 Stack in Python](#)  
A fully modular, real-time autonomy framework developed in **Python** using **ROS 2 Humble**, this stack is the central nervous system of our AUV. It handles everything from high-level mission logic to low-level motor control, enabling the robot to think, act, and adapt underwater.

#### 🔧 Key Capabilities
- **🧠 Node-Based Architecture**: Separate ROS 2 nodes for control, perception, mission planning, and communication.
- **🌐 Processor-Controller Interface**: ROS 2 topics and services bridge the Jetson Nano with the Teensy 4.1 (via Serial/UDP).
- **📡 Sensor Integration**: Real-time IMU, depth sensor, and camera data streaming for localization and feedback loops.
- **🔀 Autonomous & Manual Modes**: Seamless switching between autonomous mission execution and joystick-based teleoperation.
- **📷 Vision & UI Integration**: Works in sync with OpenCV pipelines for object detection and a PyQt-based GUI for live feedback.

#### 🏁 Outcome
> This ROS 2 stack was the foundation of our winning run at **SAUVC 2025**, helping us secure **🥈 2nd place worldwide** with stable communication, reliable control, and fully autonomous mission execution.

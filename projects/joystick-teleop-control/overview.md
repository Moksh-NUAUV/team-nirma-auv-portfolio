### [🎮 Joystick Teleoperation System](#)  
Built a robust **manual control system** using a joystick interface on the **Jetson Nano**, allowing operators to take over machine control during the competition.

#### 🔧 Key Capabilities
- **🎮 Pygame Joystick Node**: Captured joystick input using Python’s `pygame` library and published commands to ROS 2 topics.
- **⚙️ Custom Teleop Node**: Interpreted joystick inputs for directional control, depth adjustment, yaw rotation, and kill switch functionality.
- **🔀 Mode Switching**: Enabled seamless transition between manual and autonomous modes using button flags.
- **📡 Serial Command Relay**: Sent control commands from Jetson to Teensy 4.1 using ROS → Serial pipeline for real-time actuation.

#### 🏁 Outcome
> Provided a **reliable fallback and testing interface** that ensured safety during live runs and allowed precise control during debugging and development.

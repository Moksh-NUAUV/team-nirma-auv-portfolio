### [🔄 Stability Algorithm – PID Control](#)  
Designed and tuned a **PID-based control system** to maintain underwater stability and orientation during autonomous missions.

#### 🔧 Key Capabilities
- **🌀 3-Axis PID Loops**: Separate PID controllers for:
  - **Roll**, **Pitch**, **Yaw** (IMU data)
  - **Depth** (pressure sensor)
- **⚙️ Dynamic Tuning**: PID constants tuned empirically through test tank trials for optimal response and minimal oscillation.
- **🔁 Real-Time Feedback**: Control loop updated at high frequency with tight sensor-actuator feedback cycles.
- **🧭 Heading Hold**: Maintained target yaw angles with minimal overshoot for consistent navigation.

#### 🏁 Outcome
> Delivered **precision stabilization** underwater, critical for tasks like gate traversal, object interaction, and docking.

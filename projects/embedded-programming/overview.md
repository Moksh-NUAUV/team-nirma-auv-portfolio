### [⚙️ Embedded Programming – Teensy 4.1](#)  
Developed the low-level firmware for the AUV’s microcontroller using **C/C++ on the Teensy 4.1** platform. This firmware is responsible for real-time motor control, sensor data processing, and maintaining vehicle stability underwater.

#### 🔧 Key Capabilities
- **📡 Sensor Integration**: Interfaced with IMUs (BNO08x), pressure sensors, and ESCs via I2C, UART, and PWM.
- **🌀 PID-Based Stability Algorithm**: Implemented finely tuned **PID control loops** for:
  - Roll, pitch, and yaw stabilization (from IMU)
  - Vertical positioning (from pressure sensor)
- **🎯 Control Tuning**: Conducted underwater trials to empirically tune PID constants for responsive yet smooth movement.
- **🔁 Feedback Loops**: Real-time loop execution at consistent intervals, ensuring accurate error correction.
- **📬 Processor Communication**: Received commands from the Jetson via Serial/UDP, with telemetry feedback sent back to ROS nodes.
- **🛡️ Fail-Safe Handling**: Watchdog timers and conditional overrides to ensure safe fallback behavior during mission anomalies.

#### 🏁 Outcome
> This embedded layer delivered **highly stable and reliable AUV behavior**, enabling precision movement and robust mission execution in dynamic underwater environments.

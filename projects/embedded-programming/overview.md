### [⚙️ Embedded Programming – Teensy 4.1](#)  
Developed low-level control firmware for the AUV using **C/C++ on Teensy 4.1**. This firmware manages real-time sensor communication, motor commands, and interfaces directly with the high-level ROS 2 system running on the main processor.

#### 🔧 Key Capabilities
- **📡 Sensor Drivers**: Integrated IMU (BNO08x, BNO055, MPU-6050), pressure sensors(BAR-30), and thruster ESCs using UART, I2C, and PWM.
- **📬 Command Interface**: Custom Serial/UDP protocol for bidirectional communication with Jetson Nano (ROS 2 processor).
- **🧠 Control Modes**: Implemented autonomous, manual override, and hybrid control logic.
- **🛡️ Fail-Safe Mechanisms**: Watchdog timers and timeout conditions to trigger safe-stop behavior in case of communication or sensor failure.

#### 🏁 Outcome
> Enabled seamless and reliable low-level control of the AUV, with responsive actuation and smooth integration into the broader autonomy stack.

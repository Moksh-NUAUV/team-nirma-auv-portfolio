### [⚙️ Embedded Programming – Teensy 4.1](#)  
Developed the low-level firmware for the AUV’s microcontroller using **C/C++ on the Teensy 4.1** platform. This firmware is responsible for real-time control, sensor fusion, and interfacing with the main ROS 2 system.

#### 🔧 Key Capabilities
- **📡 Sensor Integration**: Interfaced with IMUs (BNO08x), pressure sensors, and motor drivers via I2C, UART, and PWM.
- **🔁 Feedback Loops**: Processed sensor data onboard and maintained tight control loops for heading, depth, and orientation.
- **📬 Communication with Processor**: Implemented custom Serial/UDP protocol to receive ROS-based commands and send back telemetry.
- **🛠️ Fail-Safe Handling**: Designed watchdog timers and fallback behaviors to ensure system safety in case of comms loss or sensor failure.
- **🎛️ Switchable Modes**: Supported manual override, autonomous control, and hybrid modes based on incoming mission flags.

#### 🏁 Outcome
> This firmware provided a **robust control layer** for the AUV, enabling responsive actuation and reliable performance even in noisy underwater environments.

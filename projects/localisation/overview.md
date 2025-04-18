### [📍 Localization using Ping Echosounders](#)  
A custom underwater localization system leveraging **two 1D Ping Echosounders** to triangulate position in a constrained pool environment. This setup provided reliable and low-latency localization without relying on GPS or expensive DVL systems.

#### 🔧 Key Capabilities
- **📐 Triangulation Algorithm**: Used time-of-flight data from two orthogonally mounted Ping sensors to estimate 2D position relative to the pool boundaries.
- **🛠️ Sensor Calibration**: Applied median filtering and offset correction for consistent readings in varying water conditions.
- **📊 ROS 2 Integration**: Sensor data published as ROS 2 messages, feeding into the central navigation node for path planning.
- **🎯 Real-Time Updates**: Localization data updated in real-time and visualized via custom PyQt GUI.

#### 🏁 Outcome
> Enabled the AUV to **self-localize within the arena** during tasks such as gate traversal and docking, significantly improving path consistency and mission execution under autonomous mode.

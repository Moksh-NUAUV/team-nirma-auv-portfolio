### [📍 Barcode Vision Mapping System](#)  
Developed a **real-time barcode localization system** that enables the AUV to autonomously map and navigate based on barcode markers in its environment using **OpenCV** and **ROS 2**.

#### 🔧 Key Capabilities
- **📷 Barcode Detection**: Used OpenCV’s `findContours` and `HoughCircles` to detect barcode markers in the AUV's camera feed.
- **🔀 ROS 2 Integration**: Barcode positions published as ROS 2 messages, feeding into the navigation stack for autonomous movement.
- **🧠 Real-Time Mapping**: Processed visual data to localize barcodes within the pool, enabling the AUV to map its environment.
- **📏 Accurate Localization**: Combined barcode detection with depth and IMU data for precise spatial awareness in 2D/3D coordinates.
- **🚀 Autonomous Navigation**: Integrated into mission execution scripts, allowing the AUV to plan paths and complete tasks based on detected barcode positions.

#### 🏁 Outcome
> The barcode vision system allowed the AUV to **autonomously localize and navigate** to target areas, enhancing task completion accuracy during ROBOFEST 4.0 and improving overall system reliability.

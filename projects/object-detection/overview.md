### [🎯 Object Detection Algorithm – YOLOv5](#)  
Implemented a fast and reliable **object detection pipeline** using **YOLOv5**, enabling the AUV to visually identify mission-critical elements like gates, markers, and drop zones during autonomous runs.

#### 🔧 Key Capabilities
- **📦 YOLOv5 Model**: Trained on a custom dataset of underwater images including gates, markers, and props under varied lighting and turbidity.
- **🧠 Real-Time Inference**: Runs directly on the **Jetson Nano GPU**, ensuring minimal latency for real-time decision-making.
- **🔗 ROS 2 Integration**: Detection results published as ROS 2 topics and passed to mission logic nodes for autonomous actions.
- **📸 Camera Feed Overlay**: Detected objects annotated live in the PyQt GUI for debugging and operator awareness.

#### 🏁 Outcome
> Enabled the AUV to **autonomously detect and react to mission elements** during tasks, significantly boosting performance and confidence during SAUVC trials and final runs.

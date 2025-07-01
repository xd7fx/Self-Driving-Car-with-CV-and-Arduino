# Self-Driving Car using CV & ROS

A fully functional AI-powered prototype car using **Computer Vision** and **ROS (Robot Operating System)**. This car is capable of autonomous navigation, lane detection, and turn recognition using real-time image processing and embedded systems.

![image](https://github.com/user-attachments/assets/8ffa31cb-aae5-45fa-80f0-f70902db1ffc)

---

## 🚀 Features

- Autonomous lane following with smooth steering
- Real-time lane detection using sliding windows
- Path direction estimation with Optical Flow
- Integration with ROS for modular robotics control
- Jetson Nano for accelerated edge processing
- Live camera streaming and decision making
  
![image](https://github.com/user-attachments/assets/a013ecb1-6fab-4be7-b01d-d329c1671ff5)

---

## 🤝 Technologies Used

| Category | Tech |
|--|--|
| CV & ML | OpenCV, Optical Flow, Perspective Transform |
| Robotics | ROS (Noetic), Arduino, Motor Shield |
| Hardware | Jetson Nano, HC-SR04, L298N, USB Cam |
| Languages | Python, C++ |
| Communication | Serial (UART), ROS Topics |

![image](https://github.com/user-attachments/assets/622b52d3-aa40-4256-958f-c93a3e10dcf6)
![image](https://github.com/user-attachments/assets/c5c3833c-8e90-479f-96bb-447d4947908c)

---

## ⚙️ Hardware Components

- Jetson Nano Developer Kit
- Arduino Uno R3
- L298N Motor Driver Shield
- 4x TT Gear Motors + Wheels
- Ultrasonic Sensor (HC-SR04) on Servo
- 3x 18650 Battery Holder
- USB HD Webcam
- Chassis & Mounts (Acrylic)
- Power Switch, Breadboard & Jumper Wires
- 
![image](https://github.com/user-attachments/assets/8fe69467-768e-4b55-9109-928dc677d761)
![image](https://github.com/user-attachments/assets/c936426f-6e61-425b-bd59-dc584359986b)
![image](https://github.com/user-attachments/assets/7c05cc44-591f-4d6a-894a-ded627101263)

---

## 🔄 System Architecture

1. **Lane Detection (OpenCV)**
   - Bird’s Eye View
   - Color Thresholding
   - Sliding Window Search
     
2. **Optical Flow** for turn angle estimation

3. **ROS Nodes**:
   - `/lane_detection_node`
   - `/motor_commands`
   - `/serial_node`

4. **Serial Communication** to Arduino for motor control
5. 
![image](https://github.com/user-attachments/assets/53eeb2a4-9df5-4a0e-a59a-f12a9fb25e12)

---

## 🎥 Output Snapshots

- Lane detection with colored mask
- Sliding window detection overlay
- Optical Flow direction vector
- ROS rqt_graph and terminal logs

https://github.com/user-attachments/assets/d38bf263-17ef-4abc-bb9a-ad5a6735198a

https://github.com/user-attachments/assets/2535d16e-2722-49be-8e94-2483244367d1

---

## 🚪 Future Improvements

- Obstacle detection with LiDAR
- Real-time YOLOv8 object detection
- GPS-based autonomous navigation
- Full ROS2 migration

---

## 📅 Timeline

- Developed as part of Full Stack Robotics Engineering program
- Completed hardware integration and CV pipeline in 2 weeks

---

## ✨ Credits

Made by **Abdulrahman Alnashri**


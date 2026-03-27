🚀 Smart Drone Control System (ABHRABHEDI – The Cloud Piercer)

A smart drone system designed for real-time manual control via code, live video streaming, and autonomous navigation, built for applications like surveillance, remote monitoring, and medicine delivery.

📌 Overview

This project focuses on building an intelligent drone system capable of:

Real-time manual control using code interface
Live video streaming from onboard camera
Autonomous waypoint-based navigation
Integration of hardware + software + communication systems

This project was developed as part of academic work at VIT Bhopal University

✨ Features
🎮 Manual Control via Code
Direct drone control using Python-based commands
Fine-grained control over movement and flight
🎥 Live Video Streaming
Real-time video feed from drone camera
Enables surveillance and monitoring
🧭 Autonomous Navigation
GPS-based waypoint tracking
Automated mission execution
⚡ Real-Time Communication
Continuous command transmission and feedback
🛑 Failsafe Mechanisms
Return-to-base on low battery or signal loss
🛠️ Tech Stack
Programming Language: Python
Libraries: OpenCV, NumPy
Hardware Platform: Raspberry Pi
Communication: Wireless (WiFi / RF)
Optional AI: TensorFlow
🏗️ System Architecture
User Input (Code Commands)
        ↓
Control Script (Python)
        ↓
Communication Module (WiFi/RF)
        ↓
Drone Flight Controller
        ↓
Motors + Sensors
        ↓
Camera Module → Live Video Feed → User
📸 Hardware Components

The drone system is built using the following components:

Raspberry Pi 4 – Image processing & control
MPU9250 – Motion sensing and stabilization
u-blox M8N GPS – Navigation
Raspberry Pi Camera – Video capture
BLDC Motors (x4) + ESCs – Propulsion
Li-Po Battery (2200 mAh) – Power
Propellers (8-inch) – Lift

👉 Refer to project documentation for visuals

🛠️ Drone Assembly
Frame construction and motor mounting
Wiring of ESCs, sensors, and controller
Integration of camera and communication modules
🧪 Testing & Implementation
Indoor stability testing
Manual flight control via code
Sensor calibration and tuning
Outdoor testing for real-world scenarios

👉 Testing phases shown in project report

🚀 Basic Drone Control Code (Sample)

Below is a simple Python example to control a drone using command signals:

import time

def takeoff():
    print("Drone taking off...")
    time.sleep(2)

def move_forward():
    print("Moving forward")
    time.sleep(2)

def move_backward():
    print("Moving backward")
    time.sleep(2)

def land():
    print("Landing drone...")
    time.sleep(2)

if __name__ == "__main__":
    takeoff()
    move_forward()
    move_backward()
    land()

⚠️ Note: This is a simplified representation. Actual implementation depends on hardware APIs and communication protocols.

🚀 Use Cases
🛰️ Surveillance (military & civilian)
💊 Medicine delivery in remote areas
🌾 Agricultural monitoring
🚨 Disaster response and rescue operations
⚙️ Installation & Setup
git clone https://github.com/riyadixit-rd/smart-drone-system
cd smart-drone-system
pip install -r requirements.txt
python main.py
🎥 Demo

Add your demo video link here

[▶️ Watch Demo Video](https://your-video-link.com)
⚠️ Challenges Faced
Integration issues with initial UI-based control system
Real-time communication delays
Hardware-software synchronization
Stabilization and calibration challenges
💡 Learnings
Real-time system design and debugging
Embedded systems and communication protocols
Drone control and navigation logic
Hardware-software integration
🔮 Future Improvements
Web/mobile-based control interface
AI-based object detection & tracking
Obstacle avoidance system
Improved battery efficiency
👩‍💻 Contributors
Riya Dixit
Mahir Bali
Devbrat Yadav
📄 License

This project is for academic and educational purposes.

⭐ Final Note

This project demonstrates strong integration of software, hardware, and real-time systems, making it a practical and scalable solution for modern drone-based applications.

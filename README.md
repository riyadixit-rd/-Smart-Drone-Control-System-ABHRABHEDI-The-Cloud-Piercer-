🚀 Smart Drone Control System

(ABHRABHEDI – The Cloud Piercer)

A smart drone system designed for manual control via code, live video streaming, and autonomous navigation, built for applications like surveillance, monitoring, and delivery.

📌 Overview

This project focuses on building an intelligent drone system capable of:

Real-time manual control using code
Live video streaming from onboard camera
Autonomous waypoint-based navigation
Integration of hardware, software, and communication systems

Developed as part of academic work at VIT Bhopal University

✨ Features
🎮 Manual Control via Code
Control drone using Python commands
Fine-grained movement control
🎥 Live Video Streaming
Real-time camera feed
Enables surveillance and monitoring
🧭 Autonomous Navigation
GPS-based waypoint tracking
Automated mission execution
⚡ Real-Time Communication
Continuous command + feedback system
🛑 Failsafe Mechanisms
Auto return-to-base on low battery or signal loss
🛠️ Tech Stack
Language: Python
Libraries: OpenCV, NumPy
Hardware: Raspberry Pi
Communication: WiFi / RF
AI (Optional): TensorFlow
🏗️ System Architecture
User Input (Code)
        ↓
Python Control Script
        ↓
Communication Module
        ↓
Flight Controller
        ↓
Motors + Sensors
        ↓
Camera → Live Feed → User
📸 Hardware Components
Raspberry Pi 4
MPU9250 (IMU Sensor)
u-blox M8N GPS
Raspberry Pi Camera
BLDC Motors (x4) + ESCs
Li-Po Battery (2200 mAh)
Propellers (8-inch)
🧪 Testing
Indoor stability testing
Manual flight control via code
Sensor calibration
Outdoor real-world testing
🚀 Basic Drone Control Code
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

Note: Actual implementation depends on drone hardware and communication protocol.

🚀 Use Cases
Surveillance (military & civilian)
Medicine delivery
Agricultural monitoring
Disaster response
⚙️ Setup
git clone https://github.com/riyadixit-rd/smart-drone-system
cd smart-drone-system
pip install -r requirements.txt
python main.py
🎥 Demo

Add your demo video here:

[▶️ Watch Demo Video](your-link-here)
⚠️ Challenges Faced
UI integration issues (switched to code control)
Communication delays
Hardware-software synchronization
Stabilization tuning
💡 Learnings
Real-time systems
Embedded + communication systems
Drone control logic
Hardware-software integration
🔮 Future Improvements
Web/mobile control interface
AI-based object detection
Obstacle avoidance
Better battery efficiency
👩‍💻 Contributors
Riya Dixit
Mahir Bali
Devbrat Yadav
📄 License

For academic and learning purposes.

⭐ Final Note

This project demonstrates strong integration of software + hardware + real-time systems, making it a practical drone solution.

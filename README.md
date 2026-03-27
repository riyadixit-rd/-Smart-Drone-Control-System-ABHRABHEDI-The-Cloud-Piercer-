<div align="center">
🚀 Smart Drone Control System
ABHRABHEDI – The Cloud Piercer








A drone system enabling manual control via code, live video streaming, and autonomous navigation.

</div>
📌 Overview

This project builds an intelligent drone system integrating hardware + software + communication systems for real-time operations.

-Manual control using code
-Live video streaming
-Autonomous waypoint navigation

Developed as an academic project at VIT Bhopal University

─────────────────────────
✨ Features
🎮 Manual Control – Python-based control interface
🎥 Live Streaming – Real-time camera feed
🧭 Autonomous Navigation – GPS waypoint tracking
⚡ Real-Time Communication – Continuous feedback loop
🛑 Failsafe System – Auto return on failure
─────────────────────────
🛠️ Tech Stack
-Language: Python
-Libraries: OpenCV, NumPy
-Hardware: Raspberry Pi
-Communication: WiFi / RF
-Optional AI: TensorFlow
─────────────────────────
🏗️ Architecture
User Input (Code)
        ↓
Control Script (Python)
        ↓
Communication Module
        ↓
Flight Controller
        ↓
Motors + Sensors
        ↓
Camera → Live Feed → User
─────────────────────────
🔧 Hardware
-Raspberry Pi 4 – Main processing unit for control and data handling
-MPU9250 (IMU) – Provides orientation and stabilization using motion sensing
-u-blox M8N GPS – Enables accurate positioning and waypoint navigation
-Raspberry Pi Camera – Captures real-time video feed for monitoring
-BLDC Motors + ESCs – Generate thrust and control motor speed
-Li-Po Battery – Supplies power to the entire drone system
-Propellers – Convert motor rotation into lift for flight
─────────────────────────
🧪 Testing
-Indoor stability testing
-Manual control via code
-Sensor calibration
-Outdoor test runs
─────────────────────────
💻 Sample Control Code
import time

def takeoff():
    print("Taking off...")
    time.sleep(2)

def forward():
    print("Moving forward")
    time.sleep(2)

def land():
    print("Landing...")
    time.sleep(2)

if __name__ == "__main__":
    takeoff()
    forward()
    land()
─────────────────────────
🚀 Use Cases
🛰️ Surveillance
💊 Medicine delivery
🌾 Agriculture monitoring
🚨 Disaster response
─────────────────────────
⚙️ Setup
git clone https://github.com/riyadixit-rd/smart-drone-system
cd smart-drone-system
pip install -r requirements.txt
python main.py
─────────────────────────
🎥 Demo
[▶️ Watch Demo](your-link)
─────────────────────────
⚠️ Challenges
-UI control integration failed → switched to code control
-Communication latency
-Hardware-software sync
-Flight stabilization
─────────────────────────
💡 Learnings
-Real-time systems
-Embedded systems
-Drone control logic
-Hardware-software integration
─────────────────────────
🔮 Future Improvements
-Web/mobile control interface
-AI-based object detection
-Obstacle avoidance
-Better battery efficiency
─────────────────────────
👩‍💻 Contributors
-Riya Dixit
-Mahir Bali
-Devbrat Yadav
─────────────────────────
⭐ Final Note

A real-world project demonstrating software + hardware + real-time system integration.

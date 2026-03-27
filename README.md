<div align="center">

# 🚀 Smart Drone Control System  
### ABHRABHEDI – The Cloud Piercer  

A drone system enabling **manual control via code, live video streaming, and autonomous navigation**.

</div>

---

## 📌 Overview  

This project builds an intelligent drone system integrating **hardware + software + communication systems** for real-time operations.

- Manual control using code  
- Live video streaming  
- Autonomous waypoint navigation  

Developed as an academic project at VIT Bhopal University  

---

## ✨ Features  

- 🎮 Manual Control – Python-based control interface  
- 🎥 Live Streaming – Real-time camera feed  
- 🧭 Autonomous Navigation – GPS waypoint tracking  
- ⚡ Real-Time Communication – Continuous feedback loop  
- 🛑 Failsafe System – Auto return on failure  

---

## 🛠️ Tech Stack  

- **Language:** Python  
- **Libraries:** OpenCV, NumPy  
- **Hardware:** Raspberry Pi  
- **Communication:** WiFi / RF  
- **Optional AI:** TensorFlow  

---

## 🏗️ Architecture  

```text
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

```

## 🔧 Hardware  

- **Raspberry Pi 4** – Main processing unit for control and data handling  
- **MPU9250 (IMU)** – Provides orientation and stabilization using motion sensing  
- **u-blox M8N GPS** – Enables accurate positioning and waypoint navigation  
- **Raspberry Pi Camera** – Captures real-time video feed for monitoring  
- **BLDC Motors + ESCs** – Generate thrust and control motor speed  
- **Li-Po Battery** – Supplies power to the entire drone system  
- **Propellers** – Convert motor rotation into lift for flight  

---

## 🧪 Testing  

- Indoor stability testing  
- Manual control via code  
- Sensor calibration  
- Outdoor test runs  

---

## 💻 Sample Control Code  

```python
import time

class DroneController:
    def __init__(self):
        self.altitude = 0
        print("Drone system initialized")

    def connect(self):
        print("Connecting to drone...")
        time.sleep(2)
        print("Connection established")

    def takeoff(self):
        print("Taking off...")
        self.altitude = 10
        time.sleep(2)
        print(f"Reached altitude: {self.altitude}m")

    def move(self, direction):
        print(f"Moving {direction}")
        time.sleep(2)

    def hover(self, duration):
        print(f"Hovering for {duration} seconds")
        time.sleep(duration)

    def return_to_base(self):
        print("Returning to base...")
        time.sleep(2)

    def land(self):
        print("Landing...")
        self.altitude = 0
        time.sleep(2)
        print("Drone landed safely")

if __name__ == "__main__":
    drone = DroneController()

    drone.connect()
    drone.takeoff()

    drone.move("forward")
    drone.move("left")

    drone.hover(3)

    drone.return_to_base()
    drone.land()
```

---

## 🚀 Use Cases  

- 🛰️ Surveillance  
- 💊 Medicine delivery  
- 🌾 Agriculture monitoring  
- 🚨 Disaster response  

---

## ⚙️ Setup  

```bash
git clone https://github.com/riyadixit-rd/smart-drone-system
cd smart-drone-system
pip install -r requirements.txt
python main.py
```

---

## 🎥 Demo  

[▶️ Watch Demo]([your-link](https://drive.google.com/file/d/1spnb-yQeddxtjqglhgIE2d4RDMa8W85P/view?usp=drivesdk))

---

## ⚠️ Challenges  

- UI control integration failed → switched to code control  
- Communication latency  
- Hardware-software synchronization  
- Flight stabilization  

---

## 💡 Learnings  

- Real-time systems  
- Embedded systems  
- Drone control logic  
- Hardware-software integration  

---

## 🔮 Future Improvements  

- Web/mobile control interface  
- AI-based object detection  
- Obstacle avoidance  
- Better battery efficiency  

---

## 👩‍💻 Contributors  

- Riya Dixit  
- Mahir Bali  
- Devbrat Yadav  

---

## ⭐ Final Note  

A real-world project demonstrating **software + hardware + real-time system integration**.


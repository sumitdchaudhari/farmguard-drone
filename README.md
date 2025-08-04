# FARMGUARD – Real-Time Crop Monitoring and Targeted Pest Control Using Drone

FarmGuard is an IoT-enabled hexacopter drone system designed to monitor crops in real time and spray pesticides precisely on affected areas. It combines ESP32-CAM, Pixhawk, and OpenCV-based image processing to deliver an efficient and eco-friendly solution for modern agriculture.

---

## 🔧 Features

- Real-time aerial crop monitoring using ESP32-CAM
- Autonomous flight via Pixhawk flight controller (ArduPilot/PX4)
- Intelligent pest detection using OpenCV
- Targeted spraying via servo-controlled nozzle system
- Wi-Fi-based image/video streaming to ground station
- Modular and upgrade-friendly architecture

---

## 🧠 Tech Stack

- **Hardware**: ESP32-CAM, Pixhawk, Hexacopter Frame, BLDC Motors, LiPo Battery, GPS Module, Servo Nozzle
- **Software**: Arduino IDE, Python, OpenCV, Mission Planner
- **Protocols**: PWM, UART, Wi-Fi Streaming

---

## 💻 Image Processing

- Platform: PC 
- Library: OpenCV (Python)
- Function: Detect stressed/pest-affected regions
- Action: Activates servo nozzle to spray pesticide only on detected areas

---

## 🛠️ Hardware Overview

| Component         | Details                                 | Purpose                                  |
|------------------|-----------------------------------------|------------------------------------------|
| **ESP32-CAM**     | 640×480 resolution camera               | Aerial imaging and live video streaming  |
| **Pixhawk**       | Flight controller (ArduPilot/PX4)       | Autonomous navigation and control        |
| **Servo Nozzle**  | Connected to Pixhawk                    | Spray pesticide when triggered           |
| **BLDC Motors**   | Brushless with ESCs                     | Provide lift and stability               |
| **GPS Module**    | External GPS + Compass                  | Waypoint flight navigation               |
| **LiPo Battery**  | 2200 mAh                                | Power source                             |
| **RC Transmitter**| FlySky 2.4GHz                           | Manual override and testing              |

---

## 📊 Performance Metrics

- 📷 Image Resolution: 640×480 (ESP32-CAM)
- 🎥 Frame Rate: ~5 FPS (live video stream)
- 📡 Wireless Range: ~50 meters (ESP32 Wi-Fi)
- ✅ Pest Detection Accuracy: ~92%
- ⚡ Spray Activation Delay: Near-instant
- 🔋 Power: 2200mAh LiPo battery

---

## 🌱 Advantages

- 💰 **Low-Cost**: Uses affordable components like ESP32
- 🌿 **Eco-Friendly**: Reduces pesticide usage with precise spraying
- 🤖 **Autonomous**: Fly, monitor, analyze, and act independently
- 🔄 **Modular Design**: Easy to upgrade components (camera, tank, controller)

---

## 🚀 Future Improvements

- Integrate thermal or multispectral sensors
- Add NDVI-based image processing
- Enable SMS/WhatsApp alerts with spray logs
- Scale for large farms using drone swarms

---

## 🛠️ How to Use

1. Upload ESP32-CAM code via Arduino IDE
2. Flash flight control firmware on Pixhawk using Mission Planner
3. Run OpenCV Python script on Raspberry Pi/PC
4. Connect system to ground station for live monitoring
5. Initiate autonomous flight and spraying via pre-set waypoints

---

## 📸 Screenshots / Media
<img width="670" height="763" alt="Farmguard_Image" src="https://github.com/user-attachments/assets/713e9842-5326-4bb2-be34-0f9f56ec148b" />
<img width="1895" height="1010" alt="Esp32cam_Monitoring_Dashboard" src="https://github.com/user-attachments/assets/3f319585-0016-4081-94a5-5cd0e7eef0fd" />

---

## 👤 Author

**Sumit Chaudhari**  
📧 chaudharisumit1483@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/sumit-chaudhari-930a53213)

---


**Sumit Chaudhari**  
LinkedIn: [https://www.linkedin.com/in/sumit-chaudhari-930a53213]

# 🚦 Traffic Signal Management System

![Python](https://img.shields.io/badge/Python-3.x-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)
![Status](https://img.shields.io/badge/Project-Active-success)
![License](https://img.shields.io/badge/License-MIT-yellow)

An **AI-powered traffic signal management system** that uses computer vision to detect vehicles and dynamically control traffic signals.

The system analyzes traffic density from multiple video feeds and adjusts signal timings accordingly to reduce congestion and improve traffic flow.  
This approach can be applied to **smart city infrastructure and intelligent transportation systems**.

---

# ✨ Features

- 🚗 **Vehicle Detection** using OpenCV and Haar cascade classifier (`cars.xml`)
- 🎥 **Multi-Lane Traffic Analysis** with multiple video inputs
- 📊 **Real-Time Dashboard** for traffic monitoring
- 🚦 **Adaptive Signal Timing** based on vehicle density
- 🎬 **Demo Simulation Videos** included
- 🏙 Designed for **Smart City Traffic Systems**

---

# 🛠 Tech Stack

- **Python 3**
- **OpenCV** – Computer vision and video processing
- **NumPy** – Numerical computation
- **Streamlit / Tkinter** *(optional)* – Dashboard visualization
- **Haar Cascade Classifier** – Vehicle detection model

---

# 🧠 System Architecture

```
Traffic Video Input
(laneA.mp4, laneB.mp4, laneC.mp4, laneD.mp4)
          │
          ▼
   Frame Processing (OpenCV)
          │
          ▼
 Vehicle Detection (cars.xml)
          │
          ▼
  Vehicle Count Per Lane
          │
          ▼
 Traffic Signal Decision Logic
          │
          ▼
 Real-Time Dashboard Display
```

---

# 📁 Project Structure

```
Traffic-Signal-Management-System
│
├── cars.xml          # Haar cascade classifier for vehicle detection
├── dashboard.py      # Dashboard visualization
├── opencv.py         # Core vehicle detection logic
├── demo.mp4          # Demo traffic simulation
├── laneA.mp4         # Lane A traffic video
├── laneB.mp4         # Lane B traffic video
├── laneC.mp4         # Lane C traffic video
├── laneD.mp4         # Lane D traffic video
└── README.md         # Project documentation
```

---

# 🚀 Getting Started

## Prerequisites

Make sure you have the following installed:

- [Python 3.x](https://www.python.org/downloads/)
- [Git](https://git-scm.com/)

Install dependencies:

```bash
pip install opencv-python numpy streamlit
```

---

# ▶️ Running the Project

### Run the dashboard

```bash
python dashboard.py
```

### Run the traffic detection script

```bash
python opencv.py
```

---

# 🎥 Demo

### Traffic Detection Demo

[![Watch Demo](https://img.youtube.com/vi/sLbDi59argg/0.jpg)](https://youtu.be/sLbDi59argg)

### Traffic Simulation Demo

[![Watch Demo](https://img.youtube.com/vi/nzNhDcnFQPw/0.jpg)](https://youtu.be/nzNhDcnFQPw)

---

# 📊 Example Output

The system detects vehicles and estimates traffic density for each lane.

Example result:

| Lane | Vehicle Count | Signal Priority |
|-----|---------------|----------------|
| Lane A | 12 | High |
| Lane B | 5 | Medium |
| Lane C | 3 | Low |
| Lane D | 7 | Medium |

---

# 🔮 Future Improvements

Possible upgrades for the project:

- Replace Haar cascade with **YOLOv8 deep learning detection**
- Real-time **CCTV traffic camera integration**
- **Reinforcement learning** for adaptive signal timing
- **Cloud dashboard** for city-wide monitoring
- Integration with **IoT traffic sensors**

---


⭐ If you found this project interesting, consider **starring the repository**.

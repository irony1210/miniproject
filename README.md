# Real-Time Lateral Sitting Posture Detection using YOLOv5

This repository provides an open-source solution for **real-time sitting posture detection** using [YOLOv5](https://github.com/ultralytics/yolov5). The system classifies sitting posture as either good or bad, aiming to promote better ergonomic habits and prevent posture-related issues.

## 🔑 Key Features

- Real-time posture detection using webcam input
- Classification of `sitting_good` vs. `sitting_bad`
- Lightweight YOLOv5s model for fast inference
- Easy to use and extend

---

## 🛠️ Built With

- Python 3.9+
- YOLOv5 (Ultralytics)

---

## ⚙️ Getting Started

### Prerequisites

- Python 3.9.x
- Git
- (Optional) NVIDIA GPU for acceleration

### Installation

#### Windows

```bash
git clone https://github.com/itakurah/SittingPostureDetection.git
cd SittingPostureDetection
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements_windows.txt


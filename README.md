
# 🔆 Hand Gesture-Based Brightness Control

A real-time Python project using OpenCV, MediaPipe, and screen brightness control libraries to dynamically adjust screen brightness based on the distance between your thumb and index finger.

## 📌 Features

- Hand tracking using MediaPipe
- Real-time distance detection between fingertips
- Dynamic screen brightness adjustment (0% to 100%)
- Python + OpenCV + NumPy based

## 🖥️ Technologies Used

- Python
- OpenCV
- MediaPipe
- screen-brightness-control
- NumPy

## ⚙️ How It Works

1. Captures webcam feed
2. Detects hand landmarks using MediaPipe
3. Measures the distance between thumb tip and index finger tip
4. Maps distance to brightness level
5. Adjusts system brightness accordingly

## 🧠 Logic Flow

### 🔁 Block Diagram
![Block Diagram](images/block_diagram.png)

### 📷 Demo Screenshot
![Demo Photo](images/demo_photo.png)

## 🚀 Getting Started

### Installation

```bash
pip install opencv-python mediapipe screen-brightness-control numpy
```

### Run the Script

```bash
python brightness_control.py
```

Wave your hand, pinch your fingers — and control the brightness without touching your keyboard!

## 📁 Files Included

- `brightness_control.py` — Main Python script
- `images/` — Block diagram and project screenshots
- `README.md` — Project overview and setup instructions

## 📄 Report

This project was developed as part of the final year academic submission.

## 📬 Contact

For questions or contributions, reach out via LinkedIn or GitHub!

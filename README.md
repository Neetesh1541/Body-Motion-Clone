# 🕺 Body Motion Clone

A real-time computer-vision project that creates a glowing mirrored body-motion clone beside the webcam feed. It uses pose landmarks to turn human movement into a cyberpunk-style visual experience.

## ✨ Features

- Real-time pose detection with **MediaPipe**
- Mirrored glowing stick-figure clone
- Dynamic visual color transitions
- Real-time **3D pose visualization** with Matplotlib
- Smooth overlay blending
- Webcam-based interaction

## 🛠️ Tech Stack

- Python 3.9+
- OpenCV
- MediaPipe
- NumPy
- Matplotlib

## 📦 Installation

```bash
pip install opencv-python mediapipe matplotlib numpy
```

## ▶️ Run

```bash
python cyberpunk_dance_clone.py
```

Press **q** to exit.

## 🧠 How It Works

1. Capture frames from the webcam.
2. Detect body landmarks using MediaPipe.
3. Mirror and offset the detected pose.
4. Render a glowing stick figure over the frame.
5. Visualize the pose coordinates in 3D.
6. Repeat in real time until the user exits.

## 🔮 Future Ideas

- Gesture-based controls
- Pose recording and playback
- Export poses as animations
- Audio-reactive visuals
- Improved landmark smoothing

## 👨‍💻 Author

Built by **Neetesh Sharma**.

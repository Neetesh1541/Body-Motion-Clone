# 🕺 Body Motion Clone

A real-time **computer-vision experience** that creates a glowing mirrored body-motion clone beside a webcam feed. Human movement is captured through pose landmarks and transformed into a cyberpunk-style visual effect.

## ✨ Features

- 🎥 Real-time pose detection with MediaPipe
- 👤 Mirrored glowing stick-figure clone
- 🌈 Dynamic visual effects and transitions
- 🧊 Real-time 3D pose visualization with Matplotlib
- ✨ Smooth overlay blending
- 📷 Webcam-based interaction

## 🧠 How It Works

```text
Webcam Feed
    ↓
MediaPipe Pose Detection
    ↓
Landmark Processing & Mirroring
    ↓
Glow / Overlay Rendering
    ↓
3D Pose Visualization
    ↓
Real-time Output
```

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python 3.9+ | Application logic |
| OpenCV | Webcam and image processing |
| MediaPipe | Pose landmark detection |
| NumPy | Numerical processing |
| Matplotlib | 3D pose visualization |

## 📦 Installation

```bash
pip install opencv-python mediapipe matplotlib numpy
```

## ▶️ Run

```bash
python cyberpunk_dance_clone.py
```

Press **`q`** to exit.

## 🔮 Future Improvements

- Gesture-based controls
- Pose recording and playback
- Export poses as animations
- Audio-reactive visuals
- Improved landmark smoothing

## 👨‍💻 Author

Built by **Neetesh Sharma**.
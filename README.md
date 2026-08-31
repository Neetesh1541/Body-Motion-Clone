# 🕺 Body Motion Clone

A real-time **computer-vision experience** that creates a glowing mirrored body-motion clone beside the webcam feed. The project uses pose landmarks to transform human movement into a cyberpunk-style visual experience.

## ✨ Features

- 🎥 Real-time pose detection with MediaPipe
- 👤 Mirrored glowing stick-figure clone
- 🌈 Dynamic visual effects and transitions
- 🧊 Real-time 3D pose visualization with Matplotlib
- ✨ Smooth overlay blending
- 📷 Webcam-based interaction

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

Press **`q`** to exit.

## 🧠 How It Works

1. Capture frames from the webcam.
2. Detect body landmarks with MediaPipe.
3. Mirror and offset the detected pose.
4. Render a glowing stick-figure clone.
5. Visualize pose coordinates in 3D.
6. Repeat the pipeline in real time.

## 🔮 Future Improvements

- Gesture-based controls
- Pose recording and playback
- Export poses as animations
- Audio-reactive visuals
- Improved landmark smoothing

## 👨‍💻 Author

Built by **Neetesh Sharma**.
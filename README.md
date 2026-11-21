# 🎭 AI Face Emotion HUD

A real-time facial emotion recognition application built with **OpenCV** and **DeepFace**. It features a futuristic Heads-Up Display (HUD) overlay that tracks and visualizes live confidence bars for five core emotions without freezing the webcam feed.

## ✨ Features
- **Real-Time Emotion Detection:** Tracks `angry`, `happy`, `sad`, `surprise`, and `neutral` expressions.
- **Lag-Free Performance:** Uses Python `threading` to run DeepFace inference asynchronously in the background while keeping the OpenCV video stream smooth.
- **Futuristic HUD Interface:** Displays a centered target bounding box with the dominant emotion percentage and a live side-panel bar chart.

## 🛠️ Tech Stack
- **Python 3.8+**
- **OpenCV (`opencv-python`)** – Webcam capture and HUD rendering
- **DeepFace (`deepface`)** – Facial emotion analysis

## 🚀 Installation & Setup

1. **Clone the repository:**
   
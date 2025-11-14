Sign Language Recognition System 🖐🤖

A real-time hand gesture recognition system that detects numerical sign language gestures (1, 2, 3, …) using Python, OpenCV, and MediaPipe.
This project captures hand gestures through a webcam, extracts landmarks, classifies gestures, and displays the recognized sign on-screen.

🚀 Features

✔ Real-time video capture using webcam
✔ Hand detection using MediaPipe
✔ Landmark extraction (21 hand keypoints)
✔ Classification of numeric gestures (1, 2, 3…)
✔ Graphical output showing detected gesture
✔ Lightweight, fast, and works on any device with a camera
✔ Easy-to-understand code (perfect for students & beginners)

🛠 Tech Stack
Component	Technology
Programming Language	Python
Computer Vision	OpenCV
Hand Tracking	MediaPipe
Model	Rule-based / ML classification

🔧 Installation

1. Install dependencies
pip install -r requirements.txt

2. Run the project
python src/main.py

🎯 How It Works

1️⃣ Webcam captures real-time video
2️⃣ MediaPipe detects hand landmarks
3️⃣ System extracts finger positions
4️⃣ Recognition logic checks hand shape
5️⃣ Output module displays recognized gesture

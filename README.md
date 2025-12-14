Face Emotion Multi-User Recognition
📌 Project Description

This project implements a real-time face emotion recognition system that can detect multiple faces simultaneously and classify their emotional states from images or live video. It uses computer vision and deep learning techniques to recognize emotions such as Happy, Sad, Angry, Neutral, Surprise, etc.

The system is designed to work with multiple users in a single frame, making it suitable for real-world applications like classroom monitoring, customer behavior analysis, and human–computer interaction.

🚀 Features

👥 Detects multiple faces in a single frame

🎭 Predicts emotion for each detected face

🎥 Supports real-time webcam input

⚡ Fast and lightweight inference

📦 Easy to run and extend

🧠 How It Works

Face Detection – Faces are detected using OpenCV-based face detectors

Preprocessing – Detected faces are resized and normalized

Emotion Classification – A CNN model predicts the emotion label

Multi-User Handling – Each face is processed independently

Visualization – Bounding boxes with emotion labels are displayed

🛠️ Tech Stack

Language: Python

Libraries: OpenCV, TensorFlow / Keras, NumPy, Matplotlib

Model: Convolutional Neural Network (CNN)

Platform: Jupyter Notebook / Python Script

pip install -r requirements.txt
python emotion_recognition.py

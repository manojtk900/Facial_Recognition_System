# Face_Recognition_login-System

# 🎯 Real-Time Facial Recognition System

A simple real-time face recognition web application built using Python, OpenCV, and Flask.

This project detects faces from a webcam feed and recognizes known individuals using the LBPH (Local Binary Pattern Histogram) algorithm.

---

## 🚀 Features

- 📷 Live webcam streaming
- 🟢 Face detection using Haarcascade
- 🧠 Face recognition using LBPH algorithm
- 🟥 Green box for recognized faces
- 🟥 Red box for unknown faces
- 🌐 Flask-based web interface
- ⚡ Real-time processing

---

## 🛠 Technologies Used

- Python 3.14
- OpenCV (opencv-contrib-python)
- Flask
- NumPy
- Haarcascade (Face Detection)
- LBPH Face Recognizer

---

## 📂 Project Structure

Facial_Recognition_System/
│
├── dataset/
│ ├── person_name/
│ ├── image1.jpg
│ ├── image2.jpg
│
├── templates/
│ └── index.html
│
├── app.py
├── train_model.py
├── face_model.yml
├── haarcascade_frontalface_default.xml
└── README.md
│
├── templates/           #
│   └── index.html       #

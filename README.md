# Face_Recognition_login-System

#  Real-Time Facial Recognition System

A simple real-time face recognition web application built using Python, OpenCV, and Flask.

This project detects faces from a webcam feed and recognizes known individuals using the LBPH (Local Binary Pattern Histogram) algorithm.

---

##  Features

- 📷 Live webcam streaming
- 🟢 Face detection using Haarcascade
- 🧠 Face recognition using LBPH algorithm
- 🟥 Green box for recognized faces
- 🟥 Red box for unknown faces
- 🌐 Flask-based web interface
- ⚡ Real-time processing

---

##  Technologies Used

- Python 3.14
- OpenCV (opencv-contrib-python)
- Flask
- NumPy
- Haarcascade (Face Detection)
- LBPH Face Recognizer

---

##  Project Structure

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





---

## 🧠 How It Works

1. The system loads training images from the `dataset` folder.
2. Faces are detected using Haarcascade.
3. LBPH model is trained and saved as `face_model.yml`.
4. During live webcam streaming:
   - Faces are detected.
   - The trained model predicts identity.
   - If confidence is high → Name is displayed.
   - If not → Marked as "Unknown".

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Facial-Recognition-System.git
cd Facial-Recognition-System2️⃣ Create Virtual Environment
python -m venv venv
.\venv\Scripts\activate

3️⃣ Install Dependencies
pip install opencv-contrib-python flask numpy

4️⃣ Prepare Dataset

Create folder structure:

dataset/
   ├── YourName/
        ├── img1.jpg
        ├── img2.jpg


Use clear front-facing images.

5️⃣ Train Model
python train_model.py


This generates:

face_model.yml

6️⃣ Run Application
python app.py


Open browser:

http://127.0.0.1:5000

🎯 Future Improvements

Face Login Authentication

Attendance System

Blink Detection

Anti-Spoofing Security

Database Integration

Deployment to Cloud

👨‍💻 Author

Manoj TK
AI & Machine Learning Enthusiast 🚀









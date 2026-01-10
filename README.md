# FACE_EXPRESSION_DETECTION
Expression Detector is a group project focused on facial expression recognition using computer vision and machine learning.

The system detects human facial expressions from images or live camera input and classifies emotions using a trained deep-learning model.

This project demonstrates the practical use of AI + OpenCV + Python in understanding human emotions.
---
📌 Project Type

Group Project

🚀 Features

🎭 Detects facial expressions (emotion recognition)

📸 Supports image input / webcam input

🤖 Machine learning–based emotion classification

🧠 Uses a pre-trained deep learning model (emotion_model.h5)

👤 Face detection using Haar Cascade (OpenCV)

🌐 Simple web-based interface

🧪 Includes testing scripts for validation

---
🗂️ Project Structure

EXPRESSION-DETECTOR/

│

├── app.py                         <!--# Main application file-->
├── ai_judge.py                  <!--  # AI logic handler-->
├── ml_emotion.py                 <!-- # Emotion prediction logic-->
├── meme_loader.py                <!-- # Meme / response loader-->
├── emotion_model.h5             <!-- # Trained ML emotion model-->
├── haarcascade_frontalface_default.xml <!-- # Face detection model-->
├── meme.json                     <!-- # Expression-to-meme mapping-->
├── test_ml.py                     # ML testing script-->
├── test_json.py                 <!--  # JSON testing script-->
├── requirements.txt              <!-- # Required Python libraries-->
├── static/                       <!-- # Static files (CSS, JS, images)-->
├── templates/                   <!--  # HTML templates-->
└── README.md
---
🧠 How It Works

Captures image or video input
Detects faces using Haar Cascade
Extracts facial features
Passes data to a deep learning model
Predicts the facial emotion
Displays the detected expression on the web interface
---
💻 Technologies Used
Python
OpenCV
TensorFlow / Keras
Flask (Web Framework)
NumPy
HTML / CSS
---
⚙️ Installation
1️⃣ Clone the Repository
```bash
git clone https://github.com/ayush-911/EXPRESSION-DETECTOR.git
cd EXPRESSION-DETECTOR
```
---
2️⃣ Create Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate      # Linux / macOS
venv\Scripts\activate         # Windows
```
---
3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
---
▶️ How to Run the Project
Run the main application:
```bash
python app.py
```
Then open your browser and visit:
```bash
http://127.0.0.1:5000/
```
---
🧪 Testing
Run test files to verify functionality:
```bash
python test_ml.py
python test_json.py
```
---
🎯 Applications

Human–Computer Interaction

Emotion-aware systems

AI-based entertainment apps

Educational AI projects

Smart user experience systems

---
👥 About the Group

This project was developed as a group project by students with a shared interest in Artificial Intelligence, Machine Learning, and Computer Vision.

Each member contributed to different aspects such as model handling, application logic, testing, and documentation.

Group Members

Aditya Gupta 

Ayush kumar Trivedi 

Aryan Gupta 

Rishab Jaiswal

---
📜 License
This project is created for academic purposes.
You may add an MIT License or institution-specific license if required.
---
---
                         Thankyou♥️♥️

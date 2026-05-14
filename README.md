Face Recognition-Based Attendance System

A smart attendance management system that uses Face Recognition and Machine Learning 
to mark attendance through a webcam automatically. Built using Python, Flask, OpenCV, Scikit-learn, and Pandas.

Features:
Face detection using OpenCV
Face recognition using KNN Classifier
Automatic attendance marking
Stores attendance in CSV format.
Add and manage users
Real-time webcam detection
Flask-based web interface

Technologies Used:
Python
Flask
OpenCV
NumPy
Pandas
Scikit-learn
Joblib

Project Structure

Face-Recognition-Attendance-System/
│
├── Attendance/
├── static/
│   ├── faces/
│   └── face_recognition_model.pkl
│
├── templates/
│   ├── home.html
│   └── listusers.html
│
├── app.py
├── haarcascade_frontalface_default.xml
└── README.md

Installation:
Clone Repository

git clone https://github.com/your-username/Face-Recognition-Attendance-System.git
cd Face-Recognition-Attendance-System

Install Required Libraries:
pip install opencv-python flask numpy scikit-learn pandas joblib

Run the Project:
In the terminal, run this command ---> flask run

Open browser:
http://127.0.0.1:5000

How It Works:
Add new users with face images
System trains the model automatically
Webcam captures live video
Faces are recognised in real time
Attendance is stored in a CSV file

Attendance Format:
Name, Roll, Time
John,101,09:30:25

Future Improvements:
Database integration
Email notifications
Deep learning face recognition
Mobile support
Cloud deployment

License
This project is licensed under the MIT License.

Author
Developed by Aaradhya Shingru

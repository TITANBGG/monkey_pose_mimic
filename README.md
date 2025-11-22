# monkey_pose_mimic
🐒 Pose Mimic – MediaPipe + OpenCV
https://www.linkedin.com/feed/update/urn:li:activity:7397973004179279872/


This project is a fun, real-time pose mimic demo.
It tracks human body movements from the webcam and maps them to a monkey character on the screen.

I built this by taking advantage of existing AI and computer vision libraries to better understand how real-time pose estimation pipelines work in practice.

🚀 Features

✔ Live webcam input
✔ Real-time pose detection
✔ Body landmarks mapped to a virtual monkey character
✔ Simple and playful desktop UI
✔ Great learning experience for computer vision workflows

🧠 Technical Overview

This project focuses on combining powerful existing libraries:

OpenCV
Captures and displays frames from the webcam

MediaPipe Pose
Detects 33 human body landmarks (shoulders, elbows, hips, etc.)

Python + NumPy
Basic angle/distance logic to determine character actions

PyQt5
Simple GUI for the application window

Goal: Not to reinvent pose estimation, but to learn by integrating AI tools into a working application.

🛠 Installation & Run

Make sure you have Python 3.12 installed (MediaPipe compatibility).

git clone https://github.com/<your-username>/monkey_pose_mimic.git
cd monkey_pose_mimic
py -3.12 -m pip install -r requirements.txt
py -3.12 main.py

📦 Tech Stack
Technology	Purpose
Python	Core development
OpenCV	Webcam & rendering
MediaPipe Pose	Landmark extraction
PyQt5	Graphical interface
NumPy	Calculations
📹 Demo

Add LinkedIn post link or GIF here
A short preview greatly increases engagement 🔥

🎯 Future Improvements

Add more custom poses and animations

Replace character with a custom asset

Improve landmark-to-animation logic

Performance optimizations

Maybe turn it into a mini-game 👀

📌 Notes

This project was developed for learning purposes by customizing and experimenting with existing open-source examples.
Huge thanks to the MediaPipe and OpenCV communities!

👋 Contact

Feedback and contributions are always welcome.
Feel free to open an Issue or a Pull Request!

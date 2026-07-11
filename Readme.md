A real-time **hand gesture-based volume control system** built with **Python**, **OpenCV**, and **MediaPipe**. This project allows users to control the system's audio volume without touching the keyboard or mouse by simply moving their fingers in front of a webcam.

Using computer vision and hand landmark detection, the application tracks the user's hand, calculates the distance between the thumb and index finger, and smoothly adjusts the system volume based on the detected gesture. The interface also displays hand landmarks, gesture information, and a real-time volume level for an intuitive user experience.

## 🚀 Features

* 🎥 Real-time hand tracking using MediaPipe
* ✋ Touchless system volume control
* 📏 Volume adjustment based on thumb–index finger distance
* 📊 Live volume percentage and visual feedback
* ⚡ Smooth and responsive gesture recognition
* 🖥️ Works with a standard webcam
* 🎯 Lightweight and easy to run

## 🛠️ Technologies Used

* Python
* OpenCV
* MediaPipe
* NumPy
* Pycaw (Windows Audio Control)
* comtypes

## 📌 How It Works

1. Captures live video from the webcam.
2. Detects the user's hand using MediaPipe.
3. Identifies the thumb and index finger landmarks.
4. Calculates the distance between the fingertips.
5. Maps the distance to the system's volume range.
6. Updates the system volume in real time while displaying visual indicators.

## 🎯 Applications

* Touchless computer interaction
* Accessibility solutions
* Smart home interfaces
* Human-Computer Interaction (HCI) projects
* Computer Vision learning
* AI and OpenCV demonstrations
# Gesture-Based Volume & Brightness Control

##  Description

This project is a real-time gesture-controlled system that allows users to adjust system volume and screen brightness using hand movements captured through a webcam. It leverages computer vision techniques to create a touchless and intuitive human-computer interaction experience.

##  Features

* Control system volume using right-hand gestures
* Adjust screen brightness using left-hand gestures
* Real-time hand tracking using MediaPipe
* Smooth and precise control based on finger distance
* Visual feedback with hand landmarks and gesture lines

## Technologies Used

* Python
* OpenCV
* MediaPipe
* NumPy
* Pycaw (for volume control)
* screen_brightness_control

##  How It Works

The system detects hand landmarks using MediaPipe and calculates the distance between the thumb and index finger. This distance is mapped to control system volume and brightness dynamically using interpolation techniques.

##  How to Run

1. Install required libraries:

   ```
   pip install opencv-python mediapipe numpy pycaw screen-brightness-control
   ```
2. Run the Python script
3. Use your webcam to control volume and brightness with hand gestures

##  Applications

* Touchless system control
* Smart home interfaces
* Assistive technology


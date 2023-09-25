###Driver Drowsiness Detection System

Detect drowsiness in real-time using a webcam to promote road safety.

Overview

This system monitors a driver's eyes with a webcam, determining drowsiness based on the Eye Aspect Ratio (EAR). If the eyes remain closed beyond a threshold, the driver is alerted with a visual and audible warning.

Requirements

Python 3.x
OpenCV
dlib
pyttsx3
scipy

Installation


Clone the repository and navigate to its directory.
Install the required packages using pip install -r requirements.txt.

Usage

Ensure the shape_predictor_68_face_landmarks.dat file is in the correct directory or adjust its path in the code. Then, run the main script to initiate drowsiness detection.

Features

Real-time monitoring using a webcam.
Accurate eye tracking with dlib's facial landmark detection.
Visual and auditory alerts for detected drowsiness.
Contributing
Contributions are welcome! For significant modifications, please open an issue for discussion.

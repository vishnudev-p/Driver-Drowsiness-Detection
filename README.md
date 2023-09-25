#Driver Drowsiness Detection System

Detect drowsiness in drivers using a simple webcam-based system to increase road safety.

Drowsiness Detection <!-- You can replace this with the path to an image or logo -->

Overview

This system uses a webcam to monitor a driver's eyes and detects drowsiness based on the rate of eye blinking. If the eyes are closed for a prolonged period, a warning is issued to alert the driver.

Requirements

Python 3.x
OpenCV (opencv-python)
Webcam

Installation
1.Clone the repository:git clone https://github.com/your_username/driver-drowsiness-detection.git
cd driver-drowsiness-detection

2.Install the required packages:
pip install -r requirements.txt

Usage
Run the main script to start the drowsiness detection:python drowsiness_detection.py

Features
Real-time drowsiness detection using a webcam.
Visual and audible alarms can be added when drowsiness is detected.
Utilizes Haar Cascades to detect face and eyes efficiently.

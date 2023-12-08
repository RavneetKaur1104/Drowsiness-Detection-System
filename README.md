# Drowsiness Detection and Alarming System

## Overview
The Drowsiness Detection and Alarming System is an advanced car safety technology designed to mitigate the risk of road accidents caused by driver drowsiness. Using cutting-edge computer vision and machine learning techniques, this software continuously monitors the driver's eye movements in real-time. When signs of drowsiness are detected, the system employs audio and visual alerts to wake up the driver, thereby preventing potential accidents and enhancing overall road safety.

## Features

### 1. Real-time Eye Tracking
   - The system utilizes high-resolution cameras and eye tracking sensors to monitor the driver's eyes continuously.
   - Captures and analyzes eye movement patterns with precision.

### 2. Drowsiness Detection Algorithm
   - Implements a machine learning algorithm that processes eye movement data to identify signs of drowsiness.
   - Factors in indicators such as blink rate, eye closure duration, and head position to determine driver alertness.

### 3. Audio and Visual Alerts
   - Triggers customizable alarms in the form of sounds or visual alerts on the car's dashboard.
   - The system dynamically adjusts the intensity of alerts based on the severity of detected drowsiness.

### 4. User-friendly Interface
   - Simple and intuitive interface for easy integration into existing car safety systems.
   - Provides real-time feedback on the driver's alertness level.

## Requirements

- Python 3.x
- OpenCV
- Dlib
- imutils
- scipy
- numpy
- argparse

## Run 
Python3 drowsiness_yawn.py -- webcam 0		//For external webcam, use the webcam number accordingly

## Setups
Change the threshold values according to your need
EYE_AR_THRESH = 0.3
EYE_AR_CONSEC_FRAMES = 30
YAWN_THRESH = 10`	//change this according to the distance from the camera















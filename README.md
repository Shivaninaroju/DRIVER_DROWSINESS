# DRIVER_DROWSINESS

## Overview

This project aims to develop a system for detecting driver fatigue and drowsiness to improve road safety. The system leverages facial landmarks detected using a shape predictor to monitor the driver's eye and facial movements, which are key indicators of drowsiness. By analyzing these features, the system can provide early warnings to prevent accidents caused by fatigue-related impairments.

## Features
**Real-time Fatigue Detection:** Monitors the driver's facial features using webcam input.
**Eye State Monitoring:** Uses eye aspect ratio (EAR) to determine whether the driver's eyes are closed, indicating drowsiness.
**Facial Landmark Detection:** Leverages the Dlib shape predictor to detect facial landmarks and analyze eye movement.
**Warning System:** Provides visual and audio alerts when fatigue or drowsiness is detected.
**User-Friendly Interface:** Simple to use with clear on-screen prompts.

## Requirements
Python 3.x
OpenCV
Dlib
NumPy
imutils

## How It Works
**Facial Landmark Detection:** The system uses Dlib’s shape predictor to detect 68 facial landmarks. These landmarks help identify the position of the eyes, which are crucial for detecting drowsiness.
**Eye Aspect Ratio (EAR):** By calculating the EAR, the system determines whether the eyes are open or closed. A value below a certain threshold indicates that the driver’s eyes are closed, signaling potential drowsiness.
**Warning Generation:** If the EAR remains below the threshold for a specified duration, the system triggers a warning sound or visual prompt to alert the driver.

## Conclusion
The Driver Fatigue and Somnolence Forewarning System is a vital step toward enhancing road safety by leveraging facial landmark detection and eye-tracking technology. By providing real-time monitoring of the driver's alertness, the system helps reduce the risk of accidents caused by drowsy driving. With the ability to detect early signs of fatigue, the system acts as a preventive measure, giving drivers timely warnings to stay alert and focused on the road. This project demonstrates the power of computer vision and machine learning in creating practical solutions for real-world challenges.

We hope this system will inspire further development and integration into more advanced driver assistance systems, contributing to a safer driving environment worldwide.


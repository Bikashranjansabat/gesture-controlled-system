# gesture-controlled-system
# Gesture Controlled System using Computer Vision

## Overview

This project implements a gesture-based human-computer interaction system that allows users to control computer functions such as mouse movement, clicking, volume control, and screen brightness using hand gestures detected through a webcam.

The system uses computer vision techniques to detect hand landmarks and interpret gestures in real time. By mapping specific gestures to system commands, this project demonstrates a touchless interface for interacting with a computer.

---

## Problem Statement

Traditional input devices such as a mouse and keyboard require physical contact. In certain situations such as accessibility applications, touchless environments, or interactive systems, gesture-based interaction can provide a more natural and efficient alternative.

This project explores the use of hand gesture recognition to control common computer operations without physical devices.

---

## Features

* Real-time hand tracking using a webcam
* Cursor movement using hand gestures
* Mouse click actions through gesture recognition
* Volume control using finger distance gestures
* Screen brightness adjustment
* Touchless human-computer interaction system

---

## Technologies Used

* Python
* OpenCV
* Mediapipe
* NumPy
* PyAutoGUI
* PyCAW (for volume control)
* Screen Brightness Control

---

## System Architecture

Webcam Input → Hand Detection → Landmark Extraction → Gesture Recognition → System Command Execution

1. The webcam captures real-time video input.
2. Hand detection identifies the hand in the frame.
3. Landmark extraction finds key points of the hand.
4. Gesture recognition interprets the finger positions.
5. Recognized gestures trigger system actions such as mouse movement, clicking, volume adjustment, or brightness control.

---

## Installation

Clone the repository

git clone https://github.com/yourusername/gesture-controlled-system.git

Navigate to the project folder

cd gesture-controlled-system

Install required dependencies

pip install -r requirements.txt

---

## Usage

Run the program

python gesture_controller.py

or run the Jupyter Notebook

jupyter notebook Gesture_Controlled_System.ipynb

Allow webcam access and use hand gestures to control the system.

---

## Gestures and Actions

| Gesture                    | Action                |
| -------------------------- | --------------------- |
| Index finger up            | Move cursor           |
| Index finger + thumb pinch | Mouse click           |
| Increasing finger distance | Increase volume       |
| Decreasing finger distance | Decrease volume       |
| Open palm                  | Pause / Neutral state |

---

## Applications

* Touchless user interfaces
* Assistive technologies
* Smart environments
* Interactive systems
* Human-computer interaction research

---

## Future Improvements

* Custom gesture training using deep learning models
* Multi-hand gesture recognition
* Gesture-based keyboard control
* Improved gesture accuracy and robustness
* Mobile camera integration

---

## Conclusion

This project demonstrates how computer vision can be used to create intuitive and touchless human-computer interaction systems. By leveraging hand gesture recognition, users can control system functions in a natural and efficient way without traditional input devices.

## Author

Bikash Ranjan
B.Tech Computer Science
Interest Areas: Artificial Intelligence, Machine Learning, Computer Vision

This project is licensed under the MIT License.


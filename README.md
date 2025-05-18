# Hand-Tracking
Hand Tracking and Volume Control

# Hand Gesture Volume Control

This project uses computer vision and hand gesture recognition to control the system's volume. By detecting the distance between the thumb and index finger using a webcam, the script dynamically adjusts the volume level. 

## Features
- Hand gesture recognition using OpenCV and MediaPipe.
- Real-time volume control mapped to the distance between the thumb and index finger.
- Volume visualization with a progress bar and percentage display.
- High frame rate for a smooth user experience.

## Demo
![Demo GIF](demo.gif)  
(*Add a GIF or image demonstrating the functionality.*)

## Requirements
- Python 3.10+
- Webcam (built-in or external)

## Dependencies
The following Python libraries are required:
- **OpenCV**: For capturing and processing video.
- **NumPy**: For mathematical operations.
- **PyCaw**: For controlling the system volume.
- **MediaPipe**: For hand tracking.

To install the dependencies, run:
```bash
pip install opencv-python numpy pycaw mediapipe comtypes

## File Structure
├── VolumeHandControl.py    # Main script for hand gesture volume control
├── HandTrackingModule.py   # Custom module for hand tracking using MediaPipe
└── README.md               # Project documentation
 
Autor:- Vivek Nile




# Hand Gesture Recognition with OpenCV

This project utilizes OpenCV to analyze hand gestures using colored tape on fingers through your laptop camera. The gestures include:
- Drawing a red line on the video when red tape is placed on one finger.
- Zooming in and out of the video based on the distance between two fingers with green tape.
- Capturing and storing the current video frame when two fingers with blue tape are combined.

## Features

- **Red Tape Gesture**: Draws a red line on the video stream when red tape is placed on top of one finger.
- **Green Tape Gesture**: Zooms in or out on the video feed based on the distance between two fingers with green tape.
- **Blue Tape Gesture**: Captures the current frame when two fingers with blue tape are combined and saves the image.

## Requirements

- Python 3.x
- OpenCV (`opencv-python`)
- NumPy

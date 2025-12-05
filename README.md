# Computer_vision
Computer Vision – Object Detection using MobileNet SSD

Real-time object detection using MobileNet SSD and OpenCV on GIF-based video input.
This project demonstrates how deep learning models can be used for fast and efficient object detection using OpenCV’s DNN module.

Project Overview

This project uses a pre-trained MobileNet SSD (Single Shot Detector) model to detect common objects from a GIF video. Each frame is processed individually, and detected objects are displayed with:
-> Bounding boxes
-> Class labels
-> Confidence percentages
-> FPS (Frames Per Second) measurement
The project is designed to run smoothly on Google Colab but can also be adapted for local systems.

Tech Stack

Python 3
OpenCV (DNN Module)
MobileNet SSD (Caffe Model)
Pillow (PIL)
NumPy
Google Colab

Features

Real-time object detection
Lightweight and fast MobileNet SSD model
GIF-based video processing
Confidence-based filtering of detections
FPS counter for performance analysis
Simple and beginner-friendly implementation

Detected Object Classes

The model supports detection of 21 object classes:
background, aeroplane, bicycle, bird, boat, bottle, bus,
car, cat, chair, cow, diningtable, dog, horse, motorbike,
person, pottedplant, sheep, sofa, train, tvmonitor

Project Structure

computer_vision/
│
├── MobileNetSSD_deploy.prototxt.txt
├── MobileNetSSD_deploy.caffemodel
├── real_time.gif
├── object_detection.ipynb
├── README.md
├── LICENSE
└── .gitignore

Installation & Setup

Run the following inside Google Colab:
pip install pillow imutils opencv-python
Upload the following files:
MobileNetSSD_deploy.prototxt.txt
MobileNetSSD_deploy.caffemodel
real_time.gif

How the Project Works

1) Loads the trained MobileNet SSD model
2) Reads frames from the GIF file
3) Converts frames to OpenCV format
4) Passes frames through the neural network
5) Draws bounding boxes and labels
6) Displays output frame-by-frame
7) Measures real-time FPS performance

Output

Objects are detected and labeled on each frame
Confidence score is displayed for every detection
FPS and total processing time are shown at the end

Author
Alen Alex Paul

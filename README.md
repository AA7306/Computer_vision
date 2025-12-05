# Computer_vision
Computer Vision – Object Detection using MobileNet SSD

Real-time object detection using MobileNet SSD and OpenCV on GIF-based video input.
This project demonstrates how deep learning models can be used for fast and efficient object detection using OpenCV’s DNN module.

Project Overview

This project uses a pre-trained MobileNet SSD (Single Shot Detector) model to detect common objects from a GIF video. Each frame is processed individually, and detected objects are displayed with:
1) Bounding boxes
2) Class labels
3) Confidence percentages
4) FPS (Frames Per Second) measurement
The project is designed to run smoothly on Google Colab but can also be adapted for local systems.

Tech Stack

1) Python 3
2) OpenCV (DNN Module)
3) MobileNet SSD (Caffe Model)
4) Pillow (PIL)
5) NumPy
6) Google Colab

Features

1) Real-time object detection
2) Lightweight and fast MobileNet SSD model
3) GIF-based video processing
4) Confidence-based filtering of detections
5) FPS counter for performance analysis
6) Simple and beginner-friendly implementation

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

1) Run the following inside Google Colab:
2) pip install pillow imutils opencv-python
3) Upload the following files:
4) MobileNetSSD_deploy.prototxt.txt
5) MobileNetSSD_deploy.caffemodel
6) real_time.gif

How the Project Works

1) Loads the trained MobileNet SSD model
2) Reads frames from the GIF file
3) Converts frames to OpenCV format
4) Passes frames through the neural network
5) Draws bounding boxes and labels
6) Displays output frame-by-frame
7) Measures real-time FPS performance

Output

Objects are detected and labeled on each frame.
Confidence score is displayed for every detection.
FPS and total processing time are shown at the end

Author,
Alen Alex Paul

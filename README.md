# YOLO-Webcam-Detection
YOLO model implementation in Jupyter Notebook with image and live webcam object detection using OpenCV
# YOLO Object Detection in Jupyter Notebook

This project demonstrates object detection using the YOLO model inside a Jupyter Notebook. 
It includes object detection on images and live webcam video using OpenCV.

## Project Description
This repository contains:
- YOLO model loading
- Image detection using OpenCV
- Real-time webcam object detection
- Simple and beginner-friendly implementation

## Features
- Works inside Jupyter Notebook
- Real-time webcam object detection
- Image detection with bounding boxes using YOLO
- Easy and clean implementation

## Repository Contents
- YOLO_Detection.ipynb — Main notebook file
- Amazon Background.jpg — Sample test image
- requirements.txt — List of dependencies

## Installation
Install the required packages using pip:
pip install ultralytics opencv-python
Or install using the requirements file:
pip install -r requirements.txt


## Running the Notebook
Start Jupyter Notebook using:

Open the YOLO_Detection.ipynb file and run the cells step-by-step.

Image Detection
The notebook performs YOLO-based object detection on a test image and displays the annotated result.

Webcam Detection
The notebook includes real-time webcam object detection.
Press q to close the webcam window.

Important
YOLO model files such as yolo11s.pt or yolov8s.pt are not included because GitHub does not allow files larger than 100 MB.

You can download the model from the official Ultralytics releases:
https://github.com/ultralytics/assets/releases

Place the downloaded .pt file in your project folder.

Future Improvements
- Add object tracking
- Use a custom-trained model
- Build a Streamlit interface

Acknowledgements
This project uses:
- Ultralytics YOLO
- OpenCV

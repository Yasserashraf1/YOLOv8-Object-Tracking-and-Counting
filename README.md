# YOLOv8-Object-Tracking-and-Counting
This project implements object tracking and counting using the YOLOv8 model on video input. The system processes each frame of a video to detect, track, and count occurrences of specific object classes in real-time.

## Overview
The primary goal of this project is to demonstrate real-time object detection, tracking, and counting using a pre-trained YOLOv8 model. The model processes video input and tracks specific objects of interest, generating an output video that visualizes bounding boxes and the total count of detected objects.

## Features
* Real-time object detection and tracking using YOLOv8.
* Object counting for specified classes (e.g., cars, bicycles).
* Bounding box visualization for detected objects in the video frames.
* Generates a video output with real-time detection and count overlays.

## Setup and Installation
**Requirements**  

Ensure you have the following dependencies installed:
* Python 3.x
* OpenCV for video processing
* Ultralytics YOLOv8 for object detection
  
**Installation**  

Install the required Python packages using pip:

```pip install ultralytics opencv-python```  

**Additional Dependencies**  

Ensure that you have _ffmpeg_ or similar video processing tools installed if required for your platform.

## Usage
1.Load the YOLOv8 Model: The pre-trained YOLOv8 model is used to detect objects in the video.  

2.Process the Video Input: Video frames are read, processed, and annotated with bounding boxes and object counts.  

3.Save the Output: The annotated video is saved with real-time object tracking and counting.  

## Video Processing Performance  

The video processing speed varies depending on the complexity of the input video and the hardware. Processing times per frame (including object detection and tracking) typically range between 150ms to 230ms.

## Project Structure  
```
├── input_video.mp4              # Input video for processing
├── output_video.avi             # Annotated output video with bounding boxes and counts
├── yolov8n.pt                   # Pre-trained YOLOv8 model
├── object_tracking.py           # Main Python script for object tracking and counting
└── README.md                    # Project documentation
```

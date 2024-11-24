# Vehicle_Detection_using_YOLO11

## Overview
YOLOv1 (You Only Look Once version 1) is a real-time object detection system that treats detection as a single regression problem. In this project, YOLOv11 has been implemented to detect vehicles in images and videos. It is designed to strike a balance between speed and accuracy, making it suitable for real-time applications like traffic monitoring and autonomous driving systems.

## Features
Real-time vehicle detection in images.
Detection of multiple types of vehicles (e.g., Ambulances, cars, trucks, bikes, buses).
End-to-end pipeline: Preprocessing, model training, and inference.
Implementation using PyTorch for flexibility and ease of customization.

## Requirements
Python 3.8 or later
PyTorch 1.11 or later
NVIDIA GPU with CUDA support (optional but recommended)
Other dependencies (see requirements.txt for details)

## Model Architecture
YOLOv11 divides the image into an 
𝑆×S grid. Each grid cell predicts bounding boxes and confidence scores for those boxes, as well as class probabilities. Key details:

Input size: 
448×448
Backbone: Modified version of GoogLeNet
Output: 
𝑆×𝑆×(𝐵×S+𝐶) tensor, where:
S: Grid size
B: Number of bounding boxes per grid cell
C: Number of classes

## Installation
Clone this repository:
git clone https://github.com/HarshGosula/Vehicle-Detection-YOLO11.git

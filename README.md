# OpenCV-Facedetection
A simple face detection project using OpenCV’s Haarcascade classifiers in Google Colab. Detects faces in uploaded images and highlights them with bounding boxes.

# OpenCV Face Detection with Haarcascades

This project implements face detection using OpenCV’s pre-trained Haarcascade classifiers in Google Colab. It allows users to upload images, process them in grayscale, and detect faces using the `detectMultiScale()` function.

## Features
✅ Uses OpenCV’s `haarcascade_frontalface_default.xml`  
✅ Runs in Google Colab with simple file uploads  
✅ Highlights detected faces with bounding boxes  

## Setup & Usage
1. Install dependencies:  
   ```python
   !pip install opencv-python-headless numpy

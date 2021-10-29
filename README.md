# AI Pose Estimation
**Goal: Real time pose detection  using MediaPipe, OpenCV and Python**

**Language: Python**

**Steps to implement AI Pose Estimation**

* Step 1: Install MediaPipe for python using pip install
* Step 2: detect hands from real time webcam feed
* Step 3: Output images using OpenCV


**Steps to implement Sign Language Detection in real time**

* Step 1: Collect data of hands, body face and save them as Numpy Arrays
* Step 2: Train a deep neural network with LSTM layers for sequences to predict the temporal component. So that we are able to prodict the action from a number of frames
* Step 3: Put it all together - perform real time sign language detection using OpenCV

**Why MediaPipie?**

MediaPipe offers cross-platform, customizable ML solutions for live and streaming media to detection hands, face and many more.

We will start with Basic Estimation of Hand pose first and then slowly build different pose estimation ( Hand Detection, Sign Language Detection in real time, Bicep Curl Counter and many more)


**References:**
* MediaPipe framework : https://github.com/google/mediapipe
* OpenCV : https://github.com/opencv/opencv
* Two Minutes Paper youtube link: https://www.youtube.com/watch?v=F84jaIR5Uxc
* Google Blog on MediaPipe Holistic — Simultaneous Face, Hand and Pose Prediction, on Device : https://ai.googleblog.com/2020/12/mediapipe-holistic-simultaneous-face.html

**MediaPipe**
![image](https://user-images.githubusercontent.com/7972158/139479519-1626eecc-dcf4-4dd0-9d47-9c5a6cf62f08.png)

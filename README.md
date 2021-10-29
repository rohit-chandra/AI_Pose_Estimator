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

**MediaPipe**
![image](https://user-images.githubusercontent.com/7972158/139479519-1626eecc-dcf4-4dd0-9d47-9c5a6cf62f08.png)
![image](https://user-images.githubusercontent.com/7972158/139479769-00090d50-1418-43b5-aec5-9d9deb77b655.png)

**References:**
* MediaPipe framework : https://github.com/google/mediapipe
* OpenCV : https://github.com/opencv/opencv
* Two Minutes Paper youtube link: https://www.youtube.com/watch?v=F84jaIR5Uxc
* Google Blog on MediaPipe Holistic — Simultaneous Face, Hand and Pose Prediction, on Device : https://ai.googleblog.com/2020/12/mediapipe-holistic-simultaneous-face.html

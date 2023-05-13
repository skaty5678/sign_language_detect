# Action Detection for Sign Language
This repository contains code for performing action detection for sign language using deep learning techniques. The code is implemented in the Jupyter Notebook.

## Overview
The "Action Detection for Sign Language" project aims to detect and recognize various sign language actions using deep learning models. The code utilizes computer vision techniques and deep neural networks to analyze video sequences of sign language gestures and predict the corresponding actions.


## Steps involved in the process

### 1. Install and import dependencies
- Installing tensorflow, mediapipe,opencv,sklearn and matlplotlib and importing other required dependencies

### 2. Keypoints using Mediapipe holistic
- get holistic model and drawing utilities.

- define a mediapipe function.

- define draw landmarks function for pose, face, left hand and right hand.

### 3.Extract keypoint values
- define extract keypoints value function.

### 4. Setup Folders for Collection

### 5. Collect Keypoint Values for Training and Testing
- all the keypoints collected using opencv and previous functions we will extract the keypoints as a numpy array.

### 6. Preprocess Data and Create Labels and Features
- Preprocess and create 3 labels for the three signs.

### 7. Build and Train LSTM Neural Network

- Build an LSTM neural network using relu nad softmax as activation functions.The neural network trained has categorical accuracy of 99.9 %.

### 8. Make Predictions and save weights
- make predictions on the test set and save the model as h5 file.

### 10. Evaluation using Confusion Matrix and Accuracy
- Evaluate using confusion matric and accuracy score.

### 11. Test in Real Time
- Detections in real time using opencv.

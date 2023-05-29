# ego-vehicle-speed-estimaion

CIVIL-459 Final Project: Vision-based Vehicle Speed Estimation

This work is a part of ”Building AV Autopilot” Project of CIVIL-459 course at EPFL.

This work is aim to solve this problem by estimating the ego vehicle speed using only frames from a single front-facing monocular camera with a mask of the lane to preserve spatiotemporal features as input and receive high performance of vehicle speed estimation as output.

#Files Structure:

"data" folder -
--------------- c3d-sports1M_weights.h5 - wights of the pre-trained model by
--------------- test.mp4 - test video
--------------- train.mp4 - train video
--------------- test_pred.txt - model prediction of test data
"Dashcam Speed - C3D.ipynb" - 3DCNN model with preprocessing pipeline
"labels.txt" - ground truth of train data (train.mp4). Each frame of train.mp4 has a label equal to the ego speed.
"3D_CNN_model.png" - architecture of 3DCNN model
"requirements.txt" - required libraries
"val_loss.png" - graphic of validation loss on test data

#3D CNN Architecture
![Alt Text](./cnn_network.png)

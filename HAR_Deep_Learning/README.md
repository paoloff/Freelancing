# Human Activity Recognition using Deep Learning

In this project, I applied Deep Learning for processing signals extracted from 7 motion sensors for the task of Human Activity Recognition.

The Deep Learning Model is a combination of a CNN and a LSTM model inspired by published models on the literature [1,2]. The input of the model are the 7 signals from the sensors which are collected at 128 Hz for 1.2 second. The output of the model are the proabilities that the user is performing one of three activities:

1. Walking
2. Stair Climbing
3. Stair Descending

The model was trained on data collected by the client. The final performance of the model was:

- Accuracy: 95 %
- Precision, Recall and F1 scores for all three activities: > 95%

References:
[Subject Independent Human Activity Recognition with Foot IMU Data](https://ieeexplore.ieee.org/document/9066010)
[A CNN-LSTM Approach to Human Activity Recognition](https://ieeexplore.ieee.org/document/9065078)

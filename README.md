# Classification with ANN :
Deep Learning Project for AKBANK Deep Learning Bootcamp.

![image](https://github.com/user-attachments/assets/0e4741ca-7929-4c2f-8bde-da2a9f78abec)



# Project Title :
Fish Classification with ANN

#### Overview
This project implements an artificial neural network (ANN) for the classification of fish species using a large-scale fish dataset. The goal is to accurately classify images of fish into different species based on visual features.

Dataset Source: A Large Scale Fish Dataset

Description: The dataset consists of images of various fish species. Each image is labeled with the corresponding species.

#### Key Steps
Data Loading: Images and labels are loaded from the dataset.

Data Preprocessing: Images are resized, normalized, and converted to a numerical format suitable for input into the ANN.

One-Hot Encoding: Labels are encoded using one-hot encoding for multi-class classification.

Model Building: A sequential model is built with several layers, including dropout layers to prevent overfitting.

Model Training: The model is trained on the training set, and its performance is validated on the test set.

Results Visualization: Training and validation loss, as well as accuracy, are plotted to visualize the model's performance.

#### General Observation:

The training accuracy and validation accuracy generally increase with each epoch.

Loss values decrease with each epoch, meaning the model's error is gradually reducing.

The difference between training accuracy and validation accuracy is important for assessing the risk of overfitting. In particular, there are slight drops in validation accuracy during Epoch 7 and Epoch 8, but overall, the model shows good performance.


Kaggle Notebook Link : https://www.kaggle.com/code/ncikabak/classification-with-ann







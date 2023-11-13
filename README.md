# Rock-Paper-Scissors-Image-Classification

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1BEeFoD9iC3PcokE3W8DsUZ_lmKnB_kKK" width="450" height="300" />

In this project, I am using **Convolutional Neural Network (CNN)** to classify hand gesture images of rock, paper and scissors.
This project is part of [dicoding](dicoding.com) project submission in Machine Learning Developer class.

## Import Library and Download the Dataset
This project is created using TensorFlow, Numpy and Matplotlib among others. <br>

## Image Augmentation using ImageDataGenerator
ImageDataGenerator is used for data train and data validation. We can use ImageDataGenerator for data preprocessing, separating train and validation data, and image Augmentation. **Image Augmentation** is a technique to increase the volume of data train by duplicating the data with various parameter.

## Create CNN Model and Model Training
For CNN model, we will define the convolutional layer and Pooling layer. We also create callbacks to stop training process when desired model accuracy is achieved.

## Model Evaluation
We use accuracy for our metrics. 
| Metrics | Training Score | Validation Score |
| --- | --- | --- |
| Accuracy | 0,9700 | 1,000 |
| Loss | 0,1345 | 0,1484 |

## Recommendation
Various technique could be used to increase the accuracy and decrease the loss of the model. Some suggestion are:
- Transfer Learning using VGG16, ResNet and AlexNet
- Add padding and stride in convolutional layer
- Understanding Impact Learning Rate in Neural Network
- Dropout Regularization in Deep Learning

<br>

Thank you for visiting my repository!! 😀🙌

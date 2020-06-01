# Dog Breed Classifier
This project is part of Udacity's Deep Learning Nanodegree course. The whole project is implemented in Pytorch libraray. Other dependencies are given in requirements.txt. 

## Overview
The project is an application Convolutional Neural Networks and aims to develop a pipeline which can be used in web or mobile app to process user-supplied images. Our model tries to predict the true breed of dog if supplied with a dog image and tries to predict a resembling dog breed when supplied with images of human faces. 

## Datasets
* [Dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)
* [Human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip)

##  Concepts Used
**1**. Used the HaarCascade Classifier from OpenCV library to detect human faces in supplied images and used the pretrained VGG16 model to detect dog in images.<br>
**2**. Implemented a Convolutional Neural Network from scratch to model the solution as a first attempt but it turned overly simplified with just an accuracy 11% in 20 epochs.<br> 
**3**. To improve the accuracy , used Transfer Learning on a pretrained Resnet50 model to do the job . It turned to be a good choice with an accuracy of 73% in just 20 epochs. Training it for more epochs will improve the accuracy. 
 

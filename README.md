# Garbage-Recognition
Capstone project for NEU EAI6000 to identify the type of garbage using Neural Networks

EAI6000 capstone project
Group members: \ Fedor Grab \ Salman Rafiullah \ Jing Lou

Goal:
Classify which type of garbage is provided on the image. This is an image recognition task

Publicy available dataset

It consists of 6 different classes of garbage: cardboard (393), glass (491), metal (400), paper(584), plastic (472) and trash(127). Summary 2467 images.

To solve this task it is a good idea to use [Transfer Learning (TL)] (https://machinelearningmastery.com/how-to-use-transfer-learning-when-developing-convolutional-neural-network-models/). TL is a technique when already developed and trained models for a one type of classification problem are used to solve different classification problem.

Three of the most popular models are as follows:

VGG (e.g. VGG16 or VGG19).
GoogLeNet (e.g. InceptionV3).
Residual Network (e.g. ResNet50).
Plan:
Load dataset of garbage images
Prepare data:

Change the input shapes of data to be consistent
Normilize it
Prepare classification labels array
Split data on train and split sets
Implement a few different models and try to fit model to it

Choose the best model
Classify test data and count model accuracy
Summarize the work with some insights, explain how it is could be implemented in a real-world problem
By the end of the project we expect a Neural Network model classifying a garbage to one of the 6 given above garbage type with accuracy more than 90%. It can be a complicated challenge due to the fact that provided dataset seems to be difficult to classify. Also number of images

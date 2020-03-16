# Garbage-Recognition
Capstone project for NEU EAI6000 to identify the type of garbage using Neural Networks

EAI6000 capstone project
Group members: \ Fedor Grab \ Salman Rafiullah \ Jing Lou

Goal:
Classify which type of garbage is provided on the image. This is an image recognition task

Publicy available dataset

It consists of 6 different classes of garbage: cardboard (393), glass (491), metal (400), paper(584), plastic (472) and trash(127). Summary 2467 images.

To solve this task it is a good idea to use [Transfer Learning (TL)](https://machinelearningmastery.com/how-to-use-transfer-learning-when-developing-convolutional-neural-network-models/). TL is a technique when already developed and trained models for a one type of classification problem are used to solve different classification problem.

Three of the most popular models are as follows:

1. VGG (e.g. [VGG16](https://www.kaggle.com/keras/vgg16) or [VGG19](https://www.kaggle.com/keras/vgg19)).
2. GoogLeNet (e.g. [InceptionV3](https://software.intel.com/en-us/articles/inception-v3-deep-convolutional-architecture-for-classifying-acute-myeloidlymphoblastic)).
3. Residual Network (e.g. [ResNet50](https://www.kaggle.com/keras/resnet50)).

Plan:
1. Load dataset of garbage images
2. Prepare data:

  1. Change the input shapes of data to be consistent
  2. Normilize it
  3. Prepare classification labels array
  4. Split data on train and split sets
  5. Implement a few different models and try to fit model to it

3. Choose the best model
4. Classify test data and count model accuracy
5. Summarize the work with some insights, explain how it is could be implemented in a real-world problem

By the end of the project we expect a Neural Network model classifying a garbage to one of the 6 given above garbage type with accuracy more than 90%. It can be a complicated challenge due to the fact that provided dataset seems to be difficult to classify. Also number of images

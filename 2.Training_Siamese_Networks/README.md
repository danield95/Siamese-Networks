# Training Siamese Networks

## Introduction

In this mini-project, I will learn how to train siamese networks with Keras, TensorFlow, and Deep Learning.

## Goal

Using the siamese network implementation, I will be able to:

- Present two input images to our network.
- The network will predict whether or not these two images belong to the same class (i.e., verification).
- I’ll then be able to check the confidence score of the network to confirm the verification.

## Input 

The [MNIST](http://yann.lecun.com/exdb/mnist/) handwritten digit dataset.

## Output

<img src="https://github.com/danield95/Siamese-Networks/blob/main/2.Training_Siamese_Networks/output/plot.png" width="400" height="300">

Figure above shows the training history over the course of 10 epochs. The model appears fairly stable, and given that our validation loss is lower than our training loss, it appears that I could further improve accuracy by incresing the number of epochs. 


Examining the output directory, there a directory named siamese_model:
This directory contains the serialized siamese network. Next week I will learn how to take this trained model and use it to make predictions on input images.

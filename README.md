# Landscape-Generation-and-Classification
Exploring changes in landscape over time due to natural processes as well as climate change using computer vision models

## Abstract 
The architecture of various landscapes continues to change as humans are developing. This project outlines how deep learning models for computer vision can be utilized to classify and generate images of landscape. For the primary classification model, the team incorporated the EfficientNet architecture to classify landscapes, while the primary generational model is a variational autoencoder. Two public datasets were used and processed in order to train the neural network models. Some of the data processing techniques that were applied include image normalization of pixels. Image augmentation was further used to address class imbalance. The baseline CNN obtained approximately a 68\% accuracy on test data, while the EfficientNet model has achieved approximately 79\% accuracy. Additionally, both the autoencoder and variational autoencoder managed to capture image colour and general spatial features, however the baseline autoencoder produces clearer images.

## Overview 

![Project Pipeline](https://github.com/[100emoji]/Landscape-Generation-and-Classification/blob/main/images/fig1.jpg?raw=true)

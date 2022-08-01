# DeepLearningCNN

This repository contains code to build Convolutional Neural Networks (CNN) using Tensorflow library and image processing tools. Networks are made by reading Tensorflow guides and documentation, their use are primarily for personal learning and exploring, possibly utilised in future CNN projects (e.g my [Image Caption generator](https://github.com/4ndrelim/imageCaptionGenerator)).

## Basic Convolutional Network
Here a simple network is constructed using tensorflow's models API, with convolutional layers and max pooling. See [here](cifar-cnn.ipynb).

## Applying Transfer Learning
Often, there are experts that have trained, fine-tuned and optimize their networks over a large training pool of example, and this trained network can be abstracted and used in most other cases as well. Rather than train a network from scratch, here i experimented with Tensorflow's Mobile Net V2 pre-trained model to do classification. See [here](transfer-learning.ipynb).

## Exploring Data Augmentation
Data augmentation helps not only to expand the pool of training examples, but offer variation in the data, and hence regularization to the network which avoids over-fitting. It trains the network to emphasize more on the shape/intrinsic property of the object rather than its placement/orientation in a given picture. Tensorflow preprocessing library offers a wide range typical data augmentation (e.g rotation, contrast, translation) to be added into the model and applied on images. See [here](data-augmentation.ipynb).
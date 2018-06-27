# Offline Classification

This is a Keras implemention of VGGNet with some modifications. The model was trained on CIFAR10 dataset and reached a validation accuracy of 91.22%. After training, the model was converted using Apple's CoreML framework to do offline classification of objects. 

# Requirements

## python modules

- keras, tensorflow backend
- coremltools
- matplotlib
- numpy

## iOS

- Xcode
- running in an iPhone device requires an Apple's developer account

# Dataset

The dataset used was the [CIFAR10](https://www.cs.toronto.edu/~kriz/cifar.html) which consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. The dataset has 10 different classes that are completely mutually exclusive.


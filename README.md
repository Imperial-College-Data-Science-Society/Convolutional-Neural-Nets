# Machine Learning Workshop Series #3 - Introduction to Convolutional Neural Networks

## Prerequisites
- linear models
- feedforward neural networks
- basic linear algebra (matrices & vectors)

## Overview
In this workshop we will cover the basics of Convolutional Neural Networks. We will explore the application of convolution operation to image processing. We will then see how it can be integrated into the neural network framework and why this type of network greatly outperforms all previous machine learning algorithms in image processing tasks. Finally, we will learn some practical aspects of implementing ConvNets, including transfer learning.

## Agenda
1. **Theory**
    - why standard (feedforward) neural networks are not well-suited for image processing
    - what are the building blocks of convnets:
        - convolutional layers
        - pooling
        - fully-connected layers
    - how are convnets better at image processing:
        - local connectivity
        - parameter sharing (tied weights)
        - translational equivariance
    - overview of a typical convnet architecture
    - practical considerations:
        - data augmentation
        - transfer learning

2. **Codelab**
    - convolutional layers
    - pooling
    - dropout
    - convnet vs multilayer perceptron in Keras on Fashion-MNIST

## Resources
- [CS231n course notes from Stanford](http://cs231n.github.io/convolutional-networks/)
- [Goodfellow *et al* Deep Learning book](http://deeplearningbook.org)
- [Chris Olah's article on feature visualization](https://distill.pub/2017/feature-visualization/)
- [Keras tutorial on transfer learning and data augmentation](https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html)


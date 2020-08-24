# topo-augmentation-ML-protocol

Contains code for [arXiv:1908.03469](https://arxiv.org/abs/1908.03469), [Phys. Rev. Research 2, 013354 (2020)](https://doi.org/10.1103/PhysRevResearch.2.013354)

### Unsupervised learning using topological data augmentation ###

1. Produce datasets of topologically equivalent samples using topological data augmentation.

2. Train a neural network classifier for extracting the topological indices. The training is done within TensorFlow (Keras).

Oleksandr Balabanov and Mats Granath

## Prerequisites

Python 3

## Installation

The required libraries are matplotlib, numpy, jupyter, and tensorflow (tensorflow-gpu).

## The code

The code is given in format of jupyter notebooks. There are two folders correspoding to two different cases considered in our article: topological systems in 1d class AIII and 2d class A. Each folder contains seperate files for creating the datasets and for training the neural network classifiers. The pretrained neural networks for each of the cases are also provided within the folders.  




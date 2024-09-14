# Spiking Neural Network and Convolutional Neural Network-based Lip Reading

## Descsription
This uses Spiking Neural Networks [(SNNs)](https://en.wikipedia.org/wiki/Spiking_neural_network) combined with CNNs to attempt lip-reading on a [dataset of videos of speakers' faces while they talk, taken with an event-based camera](https://sites.google.com/view/event-based-lipreading). Then, I created a tutorial in a Python notebook on what I did, so anyone can learn about how to use [SNNTorch](https://snntorch.readthedocs.io/en/latest/) and PyTorch for their own research.

The tutorial first (and throughout) describes neural networks and Spiking Neural Networks. It then goes into the process from start to end, including importing libraries, loading and processing data, decisions on model architecture, creating models, training models and testing/analyzing the models, and using CUDA for GPUs.

## Below is a high-level outline of the tutorial

* Description of the problem
* Explanation of Spiking Neural Networks
* Purpose/Reason for using Spiking Neural Networks
* Plan for tackling the problem 
* Getting the data and setting up files for Colab
* Loading and exploring the data
* Downloads and Imports
* Hyperparameters
* Loading the data properly
* Explanation of how Spiking Neural Networks learn
* Creating a model that is SNN + CNN
* Defining Loss and Optimizer
* Training the model
* Exploring training results
* Creating a model that is a 3D CNN, and training/testing
* Experimentation with a 3D CNN + SNN & CNN, and training/testing

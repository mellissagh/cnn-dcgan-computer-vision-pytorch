# CNN, DCGAN & Attention-Based Computer Vision in PyTorch

This project explores deep learning methods for computer vision, including DCGAN architecture analysis, 1D CNN implementation in PyTorch, and modification of a CCNet-inspired semantic segmentation architecture for global binary image classification.

The project was completed as part of a Deep Learning for Data Science course and focuses on understanding model architecture, tensor-shape reasoning, convolutional operations, training stability, and attention-based visual representations.

## Project Overview

The project includes three main parts:

### 1. DCGAN Model Comprehension

Analyzed the Deep Convolutional Generative Adversarial Network (DCGAN) architecture, including:

- Generator and discriminator roles
- Transposed convolutions for image generation
- Strided convolutions for downsampling
- Batch Normalization for training stability
- ReLU, LeakyReLU, and Tanh activation choices
- Representation learning in unsupervised image generation

### 2. 1D CNN Implementation

Implemented and reasoned through a 1D convolutional neural network in PyTorch, including:

- Conv1D layers
- MaxPool1D
- ReLU activations
- Flattening
- Fully connected layers
- Tensor-shape calculations through the network

### 3. CCNet-Inspired Model Modification

Studied a Criss-Cross Attention Network originally designed for semantic segmentation and modified the model conceptually for global binary image classification.

This included:

- Understanding the role of the CNN backbone
- Explaining Criss-Cross Attention
- Replacing the segmentation head with a global classification head
- Using global pooling for image-level prediction
- Adapting the loss function for binary classification

## Technologies Used

- Python
- PyTorch
- Jupyter Notebook
- Deep Learning
- Computer Vision
- CNNs
- DCGANs
- Attention Mechanisms

## Key Concepts

- Convolutional neural networks
- Generative adversarial networks
- Image classification
- Image generation
- Semantic segmentation
- Attention-based computer vision
- Tensor-shape reasoning
- Model architecture modification
- Training stability

## Repository Structure

```text
cnn-dcgan-computer-vision-pytorch/
│
├── README.md
├── notebooks/
│   └── cnn_dcgan_attention_cv_project.ipynb
├── report/
│   └── .gitkeep
└── .gitignore

## notebook
The main notebook is available here:
notebooks/cnn_dcgan_attention_cv_project.ipynb

## References
This project is based on concepts from:
Radford, Metz, and Chintala, "Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks"
Huang et al., "CCNet: Criss-Cross Attention for Semantic Segmentation"
Deep learning course materials on CNNs, GANs, and attention mechanisms
# Image Classification with Transfer Learning (VGG16)

This project demonstrates how to use a pre-trained VGG16 model from PyTorch's torchvision library for image classification on a custom dataset. Transfer learning allows us to leverage pre-trained weights on ImageNet for new tasks.

## Features
- Uses a pre-trained VGG16 model for feature extraction.
- Fine-tunes the classifier for a custom dataset.
- Visualizes training and validation losses and accuracy during training.

## How to Run
1. Organize your dataset as:
    dataset/
├── train/
│ ├── class1/
│ ├── class2/
├── val/
│ ├── class1/
│ ├── class2

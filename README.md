# MRI Hippocampus Segmentation

This project aims to accurately segment the hippocampus from MRI scans using deep learning techniques. By combining U-Net and LinkNet architectures, we achieved impressive results with a Dice coefficient of 0.9938 and an F1 score of 0.9938 on the validation set.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training and Evaluation](#training-and-evaluation)
- [Results](#results)
- [Future Work](#future-work)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The hippocampus is a critical region of the brain involved in memory and spatial navigation. Accurate segmentation of the hippocampus from MRI scans is essential for diagnosing and monitoring various neurological conditions. This project leverages deep learning techniques to achieve high-precision segmentation of the hippocampus.

## Dataset

The dataset consists of labeled and original MRI scans. The images were preprocessed and augmented to enhance diversity and improve the model's performance.

## Model Architecture

The model architecture combines U-Net and LinkNet:

- **U-Net**: Implemented with an EfficientNet-B0 encoder.
- **LinkNet**: Integrated with a ResNet34 encoder for feature pyramid network (FPN) enhancement.

## Training and Evaluation

The model was trained for 12 epochs with early stopping to prevent overfitting. Data augmentation techniques were applied to the dataset to improve the model's generalization.

## Results

The model achieved a Dice coefficient of 0.9938 and an F1 score of 0.9938 on the validation set, demonstrating high accuracy in hippocampus segmentation.

## Future Work

Future work includes:

- Exploring more advanced segmentation techniques.
- Integrating the model into a clinical setting for real-time hippocampus segmentation.
- Collaborating with medical professionals to validate and improve the model's performance.

## Installation

To set up the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mri-hippocampus-segmentation.git
   cd mri-hippocampus-segmentation

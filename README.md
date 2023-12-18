# Mask-Detection-COVID19-Awarness-project

## Description
Empowering public health and safety, the Mask Detection project leverages the cutting-edge capabilities of deep learning, specifically employing the LeNet architecture. This project addresses the critical need to identify whether individuals are wearing masks, contributing to overall health awareness and compliance.

## Key Features:

- Deep Learning Integration: Harnessing the power of deep learning, the project incorporates sophisticated models for accurate mask detection.
- LeNet Architecture: Employing the LeNet convolutional neural network architecture, known for its effectiveness in image classification tasks.
- Real-time Detection: The system provides real-time detection, enabling swift and responsive monitoring in various environments.
- User-Friendly Interface: A simple and intuitive interface makes the application accessible, ensuring ease of use for both administrators and end-users.
- Alert Mechanism: In case of non-compliance (no mask detected), the system triggers alerts or notifications to prompt necessary actions.
- Scalability: The architecture is designed to be scalable, accommodating diverse settings and environments for widespread implementation.

## Overview

This is a project that is designed for the covid-19 pandemic. This will detect whether a person is wearing mask properly or not along with the percentage.

- Model used : LeNet with 2 conv2d layer and 2 maxpool layer.

- Activation function : relu.

- Optimizator : Adam.

- Learning rate : 0.001.

- Loss Function : Cross Entropy.

- Training accuracy : 95%.

- Validation accuracy : 97.5%.

## Analysis

The model was trained with a basic LeNet configuration and the results were not promising. It was then optimized by adding few other Convolutional layers and the observations were noted.

| Model  | Learning Rate |  Accuracy(%) |
| ------------- | ------------- | ------------- |
| LeNet - Basic Architecture  | 0.01  | 85%  |
 LeNet - plus 2 conv2D  | 0.01  | 72% |
|   | 0.001  | 95%




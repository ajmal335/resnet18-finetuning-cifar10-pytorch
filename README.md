# ResNet18 Fine-Tuning on CIFAR-10 (PyTorch)

## Project Overview

This project demonstrates transfer learning by fine-tuning a pretrained ResNet18 model on the CIFAR-10 dataset using PyTorch.

Instead of training a CNN from scratch, a pretrained ResNet18 model trained on ImageNet is adapted to classify the 10 CIFAR-10 classes.

---

## Features

- Pretrained ResNet18
- Fine-Tuning (Layer4 + Fully Connected Layer)
- Image Resizing (224×224)
- Data Augmentation
- ImageNet Normalization
- CrossEntropy Loss
- Adam Optimizer
- GPU Support
- Model Saving

---

## Dataset

CIFAR-10

Classes:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

---

## Model Pipeline

Input Image
↓
Resize (224×224)
↓
Data Augmentation
↓
ImageNet Normalization
↓
Pretrained ResNet18
↓
Fine-Tuning Layer4
↓
Fully Connected Layer
↓
Prediction

---

## Technologies

- Python
- PyTorch
- Torchvision
- NumPy

---

## Results

Test Accuracy: 92.56%

---

## Future Improvements

- Learning Rate Scheduler
- Early Stopping
- Mixed Precision Training
- Gradual Unfreezing

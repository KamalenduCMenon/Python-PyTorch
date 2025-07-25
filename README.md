# Python & PyTorch Projects

This repository contains several deep learning projects implemented using Python and PyTorch, demonstrating proficiency in foundational tools and frameworks for neural network development, training pipelines, and data augmentation techniques.

---

## Projects Overview

### 1. Custom Neural Network from Scratch (PyTorch)
- Implementation of a neural network (MLP or CNN) using only `torch.nn.Module` and PyTorch autograd.
- Trained on popular datasets like MNIST or Fashion-MNIST.
- Features include training metrics, loss curve visualization, and proper model saving/loading.

### 2. PyTorch Lightning Template
- A reproducible and modular training pipeline built with PyTorch Lightning.
- Includes configuration management using YAML and `argparse`.
- Supports logging via TensorBoard and Weights & Biases (WandB).
- Implements model checkpointing for easy training resumption.
- Designed for easy reuse across different models and datasets.

### 3. Data Augmentation Library (PyTorch-based)
- A lightweight data augmentation library leveraging `torchvision.transforms` and Albumentations.
- Provides common augmentation techniques for image data.
- Includes example experiments comparing model performance with and without data augmentation on CIFAR-10 or other datasets.

---

## Getting Started

### Prerequisites
- Python 3.7+
- PyTorch
- torchvision
- PyTorch Lightning
- Albumentations
- TensorBoard and/or WandB (optional, for logging)

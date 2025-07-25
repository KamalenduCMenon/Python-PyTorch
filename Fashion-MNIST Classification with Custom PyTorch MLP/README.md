# Fashion-MNIST Classification with Custom PyTorch MLP

This repository contains a PyTorch implementation of a simple **Multi-Layer Perceptron (MLP)** neural network trained to classify images from the **Fashion-MNIST** dataset.

---

## Features

- Custom MLP model built from scratch using `torch.nn.Module`.
- Training, validation, and testing on Fashion-MNIST dataset.
- Metrics including accuracy, loss, classification report, and confusion matrix.
- Training and validation loss/accuracy curves plotted.
- Model saving and loading functionality.
- Detailed evaluation with per-class precision, recall, and F1-score.

---

## Dataset

**Fashion-MNIST** contains 70,000 grayscale images of 28x28 pixels each from 10 fashion categories:

| Label | Class         |
|-------|---------------|
| 0     | T-shirt/top   |
| 1     | Trouser       |
| 2     | Pullover      |
| 3     | Dress         |
| 4     | Coat          |
| 5     | Sandal        |
| 6     | Shirt         |
| 7     | Sneaker       |
| 8     | Bag           |
| 9     | Ankle boot    |

The dataset is split into 60,000 training and 10,000 test images.

---

## Installation

Make sure you have Python 3.7+ installed. Then install the required dependencies:

```bash
pip install torch torchvision matplotlib scikit-learn seaborn

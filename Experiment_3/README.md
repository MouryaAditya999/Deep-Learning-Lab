# Experiment 3 - Convolutional Neural Networks (CNN)

## Course

**CS3807 - Deep Learning Laboratory**  
**B.Tech Artificial Intelligence & Data Science**  
**Shiv Nadar University Chennai**  
**Academic Year:** 2026-27

---

## Objective

To understand and implement Convolutional Neural Networks (CNNs) for
image classification using TensorFlow/Keras.

---

## Dataset

**CIFAR-10 Dataset**

- Training images: 50,000
- Testing images: 10,000
- Number of classes: 10
- Image size: 32 × 32 × 3

### Classes

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

## Topics Covered

- Convolution operation
- Convolution kernels
- Kernel size comparison
- Stride and padding
- Feature map visualization
- Max pooling
- Average pooling
- CNN architecture
- Model training
- Model evaluation
- Classification report
- Confusion matrix

---

## CNN Architecture

The CNN architecture used in this experiment is:

```text
Input
  ↓
Convolution
  ↓
ReLU
  ↓
Max Pooling
  ↓
Convolution
  ↓
ReLU
  ↓
Max Pooling
  ↓
Flatten
  ↓
Dense
  ↓
Softmax

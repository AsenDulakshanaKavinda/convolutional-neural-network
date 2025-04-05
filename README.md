# convolutional-neural-network

# 🧠 Types of Convolutional Neural Networks (CNNs)

A curated collection of popular CNN architectures implemented in PyTorch/TensorFlow with descriptions, diagrams, and **best use cases**.

---

## 📚 Table of Contents

- [Overview](#overview)
- [CNN Architectures](#cnn-architectures)
  - [1. Basic CNN](#1-basic-cnn)
  - [2. VGGNet](#2-vggnet)
  - [3. Inception (GoogLeNet)](#3-inception-googlenet)
  - [4. ResNet](#4-resnet)
  - [5. DenseNet](#5-densenet)
  - [6. MobileNet](#6-mobilenet)
  - [7. EfficientNet](#7-efficientnet)
  - [8. RCNN Family](#8-rcnn-family)
  - [9. YOLO](#9-yolo)
  - [10. U-Net & SegNet](#10-u-net--segnet)
  - [11. 3D CNN](#11-3d-cnn)
  - [12. Siamese Network](#12-siamese-network)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## 🧾 Overview

This repository provides implementations and summaries of various CNN architectures used in computer vision, along with their ideal use cases.

---

## 🔍 CNN Architectures

### 1. **Basic CNN**
- **Description**: Simple architecture with a few convolutional and pooling layers.
- **Use Case**: Digit classification (e.g., MNIST).

---

### 2. **VGGNet**
- **Description**: Deep network with uniform 3x3 convolution filters.
- **Use Case**: Image classification, feature extraction for transfer learning.

---

### 3. **Inception (GoogLeNet)**
- **Description**: Parallel filters (1x1, 3x3, 5x5) in Inception modules.
- **Use Case**: Scalable object recognition (ImageNet).

---

### 4. **ResNet**
- **Description**: Skip connections to create deep residual learning.
- **Use Case**: Very deep image classification (e.g., ResNet-50, ResNet-101).

---

### 5. **DenseNet**
- **Description**: Each layer connects to all previous layers.
- **Use Case**: Efficient deep learning for image classification.

---

### 6. **MobileNet**
- **Description**: Lightweight with depthwise separable convolutions.
- **Use Case**: Mobile and edge AI applications.

---

### 7. **EfficientNet**
- **Description**: Scales depth, width, and resolution systematically.
- **Use Case**: High-accuracy classification with fewer parameters.

---

### 8. **RCNN Family**
- **Description**: Combines region proposals with CNNs for object detection.
  - RCNN → Fast RCNN → Faster RCNN
- **Use Case**: General object detection (e.g., pedestrian, car detection).

---

### 9. **YOLO (You Only Look Once)**
- **Description**: End-to-end real-time object detection system.
- **Use Case**: Real-time detection (self-driving cars, CCTV, drones).

---

### 10. **U-Net & SegNet**
- **Description**: Encoder-decoder architectures for segmentation.
- **Use Case**: Medical imaging, satellite image segmentation.

---

### 11. **3D CNN**
- **Description**: 3D convolutions for spatial + temporal data.
- **Use Case**: Video classification, MRI/CT scan analysis.

---

### 12. **Siamese Network**
- **Description**: Twin CNNs with shared weights for similarity comparison.
- **Use Case**: Face verification, signature matching, one-shot learning.

---


---
layout: single
mermaid: true
mathjax: true
title: Neural Networks and Their Applications
---
Welcome to my research project where I explore and compare traditional neural networks, convolutional neural networks (CNNs), and sparse CNNs using PyTorch. The project culminates in applying sparse architectures to the **Cityscapes** dataset — a real-world dataset used for autonomous vehicle vision tasks.
---

## Introduction
Neural networks are the foundation of modern AI, mimicking how the human brain processes information. Convolutional Neural Networks (CNNs) extend this by allowing networks to focus on spatial patterns — perfect for images. In this project, I take it a step further by exploring **sparse CNNs**, which reduce computational overhead while retaining accuracy, making them ideal for real-time systems like autonomous driving.
---

## Motivation & Goals

As the world moves toward intelligent systems, real-time image recognition is becoming a crucial technology. However, high computational costs limit CNN deployment in edge devices. My goal is to:

- Understand and compare basic NNs, CNNs, and sparse CNNs.
- Implement these architectures from scratch in PyTorch.
- Evaluate their performance on benchmark datasets and **Cityscapes**.
- Prepare this work to showcase technical and analytical skills to employers.
---

## Building a Simple Neural Network for Classification

Before diving into vision models, I started by implementing a basic neural network to classify images from simpler datasets such as MNIST or FashionMNIST. This served as a foundation to understand key elements of supervised learning:

- Forward and backward propagation
- Weight updates using gradient descent
- Loss functions (CrossEntropy)
- Accuracy tracking and performance visualization

[Basic Neural Network](./Basic_NN.html)
---

## From CNNs to Sparse CNNs for Semantic Segmentation

After mastering standard neural nets, I moved on to convolutional architectures and their real-world applications in autonomous systems.

- **Convolutional Neural Networks (CNNs)** were trained on downsampled images from **Cityscapes**, focusing on pixel-wise classification (semantic segmentation).
- To handle resolution loss from pooling, I implemented a **mini U-Net**, which reconstructs high-resolution predictions from low-resolution encodings.
- Finally, I investigated **sparse CNNs**, designed to ignore redundant or low-information regions (e.g., sky or blank walls), to reduce computation while maintaining accuracy.

> This evolution allowed me to explore the **trade-off between model complexity, accuracy, and speed** — critical in real-time systems like self-driving vehicles.
---

## Key Takeaways

- Neural networks are powerful, but spatial tasks require architectures like CNNs or U-Nets.
- Sparse CNNs are promising for real-time image tasks with limited compute.
- Visualization helps interpret model behavior — especially in safety-critical domains.
---

## Resources

- [GitHub Repo]()
- [Cityscapes Dataset](https://www.cityscapes-dataset.com/)
- [PyTorch Docs](https://pytorch.org/)

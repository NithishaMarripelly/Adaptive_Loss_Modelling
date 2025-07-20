# AdaFace Loss Implementation on MNIST and CIFAR-10
This project demonstrates the manual implementation of **AdaFace loss**, a state-of-the-art face recognition loss function, on two benchmark datasets—**MNIST** and **CIFAR-10**. The goal is to explore the effect of adaptive margin tuning on model performance when compared with traditional margin-based losses like ArcFace.

## Key Features
- Manual implementation of **AdaFace loss** based on academic research
- Experiments conducted on both **simple CNN (MNIST)** and **ResNet18 (CIFAR-10)**
- Enhanced generalization and robustness on mixed-quality inputs
- Tuning with dropout, batch normalization, and data augmentation to reduce overfitting

## Files Included
- `Project_MNIST.ipynb`: AdaFace loss implementation on the MNIST dataset using a custom CNN
- `Project_CIFAR10.ipynb`: AdaFace loss applied to CIFAR-10 using ResNet18
- `Memo.pdf`: Short memo summarizing project details, key findings, and comparative results with ArcFace

## References
- [AdaFace: Quality Adaptive Margin for Face Recognition](https://arxiv.org/abs/2204.00964)

> This project was completed as part of an academic exploration of robust face recognition techniques using adaptive margin learning.

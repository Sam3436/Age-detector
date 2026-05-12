# Facial Age Estimation Investigation

This project explores various Deep Learning architectures for predicting human age from facial images. The investigation covers the full pipeline from basic CNNs to unsupervised pre-training with Autoencoders and fine-tuning state-of-the-art backbones like ResNet-18.

## 📋 Project Overview
The goal of this study was to evaluate how different architectural decisions and training strategies—such as regression vs. classification and transfer learning—affect the accuracy of age estimation.

### Key Milestones:
1.  **Digit Classification Foundation**: Establishing core principles using the MNIST dataset.
2.  **Custom CNNs**: Developing regression and classification models from scratch.
3.  **Unsupervised Pre-training**: Training a Convolutional Autoencoder to learn facial features without labels.
4.  **Transfer Learning**: Comparing an Autoencoder-based classifier against a pretrained ResNet-18 backbone.

## 📊 Performance Summary
- **Best Regression Model**: Mean Absolute Error (MAE) of **5.48 years**.
- **Best Classification Model**: Accuracy of **0.710** (across 6 age categories).
- **Key Finding**: Pretrained backbones (ResNet-18) consistently outperformed custom architectures, demonstrating the power of feature transfer from large-scale datasets like ImageNet.

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.9 or higher
- NVIDIA GPU with CUDA support (Recommended for local training)

### Setup Instructions
1. **Clone the repository**:
   ```bash
   git clone <your-repo-url>
   cd <repo-name>

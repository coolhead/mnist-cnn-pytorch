# 🧠 CNN on MNIST with PyTorch & TensorBoard

This project builds and trains a simple Convolutional Neural Network (CNN) using PyTorch to classify handwritten digits from the MNIST dataset. It also uses TensorBoard for visualizing training metrics and evaluating model performance.

---

## 🎯 Objective

To implement a deep learning pipeline that:
- Uses GPU acceleration for training (CUDA)
- Tracks performance metrics using TensorBoard
- Evaluates predictions with confusion matrix and per-class accuracy
- Visualizes prediction samples

---

## 📚 Dataset

- **MNIST**: Handwritten digits (28x28 grayscale images)
- 60,000 training images, 10,000 test images

---

## 🛠️ Tech Stack

- Python 3.10
- PyTorch
- Torchvision
- TensorBoard
- Matplotlib
- scikit-learn

---

## 📈 TensorBoard Features

- Loss curves (per batch & per epoch)
- Accuracy tracking
- Model graph visualization
- Input image grids
- Optional: Parameter histograms

Launch with:

```bash
tensorboard --logdir=runs


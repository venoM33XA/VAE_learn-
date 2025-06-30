# 🧠 Variational Autoencoder on MNIST

This project implements a simple **Variational Autoencoder (VAE)** using the MNIST handwritten digits dataset. The goal is to learn a low-dimensional latent representation of the digit images and reconstruct them effectively, while exploring generative capabilities of the model.

---

## 📚 Overview

A Variational Autoencoder is a type of generative model that learns the **distribution** of input data rather than memorizing it. This implementation includes:

- Encoder and decoder architecture built using **PyTorch**
- Latent space regularized using the **KL divergence loss**
- Image reconstruction and new sample generation from latent space

---

## 📦 Dataset

- **MNIST**: 28×28 grayscale images of handwritten digits (0–9)
- Downloaded automatically via `torchvision.datasets.MNIST`

---

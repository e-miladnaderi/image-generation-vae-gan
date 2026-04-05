# Image Generation with VAE and GAN

> Deep generative models for image synthesis using Variational Autoencoders (VAE) and Generative Adversarial Networks (GAN).

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-Generative%20AI-purple?style=flat)

---

## Overview

This project explores deep generative models for image synthesis. Two architectures are implemented and compared: **Variational Autoencoders (VAE)** for learning latent space representations, and **Generative Adversarial Networks (GAN)** for high-quality image generation through adversarial training.

---

## Models Implemented

### Variational Autoencoder (VAE)
- Encoder-decoder architecture with reparameterization trick
- Latent space interpolation and sampling
- Reconstruction loss + KL divergence objective

### Generative Adversarial Network (GAN)
- Generator and Discriminator networks
- Adversarial training loop
- Image quality evaluation

---

## Features

- Full implementation of VAE and GAN from scratch in PyTorch
- Training pipelines with loss tracking and visualization
- Latent space visualization
- Side-by-side comparison of generated images from both models
- Qualitative and quantitative evaluation

---

## Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core programming language |
| PyTorch | Deep learning framework |
| torchvision | Dataset loading and transforms |
| Matplotlib | Image and loss visualization |
| NumPy | Numerical operations |

---

## Project Structure

```
image-generation-vae-gan/
├── vae/                # VAE model and training
├── gan/                # GAN model and training
├── notebooks/          # Experiments and visualizations
├── results/            # Generated images and plots
├── requirements.txt
└── README.md
```

---

## Results

- VAE produced smooth interpolations in latent space
- GAN generated sharp, realistic images after adversarial training
- Comparative analysis highlights trade-offs between the two approaches

---

## Author

**Milad Naderi Beni** - MSc Data Science, University of Naples Federico II

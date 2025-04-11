# MNIST_Generative_Models_GAN_and_VAE



A collection of generative models (GAN, VAE, and Diffusion Model) implemented in TensorFlow/Keras for MNIST digit generation and classification.

## 📋 Overview

This repository contains three distinct approaches to working with the MNIST dataset:
1. **GAN-based image generation** with a CNN classifier.
2. **Variational Autoencoder (VAE)** for latent space learning and classification.
3. **Diffusion Model** for noise-based image generation.

## 🚀 Features

### 1. GAN Implementation
- Conditional GAN architecture for digit generation
- Separate CNN classifier for evaluation
- Training pipeline with TensorFlow Dataset optimization
- Visualization of generated images and predictions

### 2. Variational Autoencoder (VAE)
- Custom sampling layer for latent space modeling
- KL divergence regularization
- Classification using latent representations
- Image reconstruction visualization

### 3. Diffusion Model
- Time-embedded U-Net architecture
- Progressive noising/denoising mechanism
- Custom training loop with EMA-like sampling
- Novel implementation of diffusion process

## 📂 Code Structure

| File                   | Description                                  |
|------------------------|----------------------------------------------|
| `gan_mnist.py`         | GAN implementation with CNN classifier       |
| `vae_mnist.py`         | VAE with latent space classification         |
| `diffusion_mnist.py`   | Diffusion model implementation               |

## 🛠️ Prerequisites

- Python 3.8+
- TensorFlow 2.10+
- Matplotlib
- Numpy

Install requirements:
```bash
pip install tensorflow matplotlib numpy

🏃 Usage

    GAN Implementation

bash
Copy

python gan_mnist.py

    Trains a GAN for 5 epochs

    Simultaneously trains a classifier on real MNIST data

    Outputs test accuracy and sample predictions

    VAE Implementation

bash
Copy

python vae_mnist.py

    Trains VAE for 5 epochs

    Trains classifier on latent space features

    Shows original/reconstructed images comparison

    Diffusion Model

bash
Copy

python diffusion_mnist.py

    Trains diffusion model for 30 epochs

    Implements custom noise scheduling

    Generates novel digits through reverse diffusion

📊 Results

All scripts include visualization of:

    Generated/reconstructed images

    Model predictions on test samples

    Training progress metrics

Example outputs:
GAN Generated Digits
VAE Reconstructions
Diffusion Samples
📚 References

    GAN - Original Paper

    VAE - Kingma et al.

    Diffusion Models - Ho et al.

    TensorFlow Documentation

🤝 Contributing

Pull requests welcome! For major changes, please open an issue first to discuss proposed changes.
📄 License

MIT License - see LICENSE for details
Copy


This README provides:
- Clear structure for different implementations
- Visual placeholder links for generated images
- Concise setup/usage instructions
- Technical context for each approach
- References to original papers
- Contribution guidelines

You may want to:
1. Replace placeholder image URLs with actual generated samples
2. Add real performance metrics from your training runs
3. Include more detailed architecture diagrams
4. Add hardware requirements/benchmarks

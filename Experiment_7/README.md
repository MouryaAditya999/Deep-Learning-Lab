
## Experiment 7: Autoencoders, Convolutional Autoencoders, Denoising Autoencoders and Variational Autoencoders

This repository contains the implementation, plots, results, and report for the CS3807 Deep Learning Laboratory experiment on autoencoders using the MNIST handwritten digit dataset.

## Objective

The experiment studies four types of autoencoder-based models:

1. Fully Connected Autoencoder (FC-AE)
2. Convolutional Autoencoder (CAE)
3. Denoising Convolutional Autoencoder
4. Variational Autoencoder (VAE)

The models are evaluated for image reconstruction, denoising, latent-space representation, and image generation.

## Dataset

**Dataset:** MNIST Handwritten Digits

- Image size: `28 × 28 × 1`
- Pixel values normalized from `[0, 255]` to `[0, 1]`
- Training subset: 10,000 images
- Test subset: 2,000 images
- Validation split: 1,000 images from the training subset
- Digits: 0–9

The digit labels are not used as reconstruction targets. The original image itself is used as the target.

## Models

### 1. Fully Connected Autoencoder

Architecture:

```text
784 → 128 → 32 → 16 → 32 → 128 → 784

# Chex-GANS

Chex-GANS is a project aimed at generating chest X-ray images using Generative Adversarial Networks (GANs). This repository contains implementations of three different GAN architectures for this task: Vanilla GANs, Wasserstein GANs (WGANs), and Deep Convolutional GANs (DCGANs).

## Overview

Chest X-ray images play a crucial role in diagnosing various pulmonary diseases. However, acquiring a large dataset of such images for training machine learning models can be challenging due to privacy and ethical concerns. Generative models like GANs offer a promising solution by generating synthetic images that closely resemble real chest X-rays.

## GAN Architectures

### Vanilla GANs

Vanilla GANs, also known as standard GANs, consist of a generator and a discriminator trained adversarially to generate realistic images.

### Wasserstein GANs (WGANs)

Wasserstein GANs introduce a different loss function, namely the Wasserstein distance, which provides more stable training and better convergence properties compared to standard GANs.

### Deep Convolutional GANs (DCGANs)


DCGANs utilize deep convolutional networks for both the generator and discriminator, enabling the generation of higher resolution and more realistic images.

## Notebooks

This repository contains Jupyter notebooks for each of the three GAN architectures:

- `Vanilla_GAN.ipynb`
- `WGAN.ipynb`
- `DCGAN.ipynb`

These notebooks provide step-by-step implementations of the respective GAN architectures along with training and evaluation procedures.

## Results

### DCGAN Architecture

<table>
  <tr>
<!--     <td><img src="https://github.com/k-Rohit/Chex-GANS/assets/93335681/d046a4e0-8f49-4e06-84b8-347107539169" alt="epoch_50_image_45"></td>
    <td><img src="https://github.com/k-Rohit/Chex-GANS/assets/93335681/09c93c98-7b47-41af-90f2-af03570a4666" alt="epoch_50_image_46"></td>
    <td><img src="https://github.com/k-Rohit/Chex-GANS/assets/93335681/26d87470-f9e0-43d8-aa8c-2cdccdc343fd" alt="epoch_50_image_48"></td> -->
    <td><img src="https://github.com/k-Rohit/Chex-GANS/assets/93335681/cb32492f-4029-4aa6-9260-2bbf1689d191">  </td>
  </tr>
</table>

## Getting Started

### Prerequisites

- Python (>=3.6)
- PyTorch
- torchvision
- Other dependencies (specified in requirements.txt)

### Installation

Clone this repository:

```bash
git clone https://github.com/your_username/Chex-GANS.git
cd Chex-GANS

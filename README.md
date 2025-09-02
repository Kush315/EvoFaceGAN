# EvoFaceGAN

EvoFaceGAN is a PyTorch Lightning-based Generative Adversarial Network (GAN) for facial aging and rejuvenation. It leverages paired and unpaired image-to-image translation to generate aged or rejuvenated faces, using custom generator and discriminator architectures.

## Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Datasets & Preprocessing](#datasets--preprocessing)
- [Configuration](#configuration)
- [Training](#training)
- [Inference](#inference)
- [Results](#results)
- [Citation](#citation)
- [License](#license)

---

## Features

- GAN-based facial aging and rejuvenation.
- Custom generator and discriminator models.
- PyTorch Lightning for modular training.
- Configurable data augmentation and training parameters.
- Preprocessing scripts for CACD and UTKFace datasets.
- Inference script for generating aged faces from input images.

---

## Project Structure

EvoFaceGan/
│
├── main.py                # Training entry point
├── infer.py               # Inference script
├── gan_module.py          # GAN model (AgingGAN) and training logic
├── models.py              # Generator, Discriminator, ResidualBlock definitions
├── dataset.py             # Custom PyTorch Dataset for image pairs
├── requirements.txt       # Python dependencies
├── timing.py              # Timing utilities
├── configs/
│   └── aging_gan.yaml     # Training configuration
├── preprocessing/
│   ├── preprocess_cacd.py # CACD dataset preprocessing
│   └── preprocess_utk.py  # UTKFace dataset preprocessing
├── pretrained_model/
│   └── state_dict.pth     # Pretrained model weights
└── mygraph.png            # Example output image

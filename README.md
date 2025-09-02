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


## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Kush315/EvoFaceGAN.git
   cd EvoFaceGAN

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt

---   

##Datasets & Preprocessing
-Supported datasets: CACD and UTKFace.
-Preprocessing scripts are provided in preprocessing/ to split images into domains (young/old).
**Example (CACD):**
```bash
python [preprocess_cacd.py](http://_vscodecontentref_/9) --image_dir /path/to/CACD/images --metadata /path/to/CACD/metadata.mat --output_dir /path/to/output
```
-hi

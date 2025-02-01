# StyleGAN K-Girl Image Generation

## Overview
This project involves training a **StyleGAN** model to generate high-quality images of K-girls (Korean-style female faces). The dataset is curated to capture the distinct aesthetic features common in K-girl images, and StyleGAN is used to create photorealistic outputs.

## Dataset
- The dataset consists of high-resolution images of K-girls.
- Images are preprocessed and resized to fit StyleGAN's input requirements.
- Data augmentation techniques such as flipping and color adjustments are applied.

## Model Training
- **Framework**: TensorFlow with NVIDIA StyleGAN implementation.
- **Hardware**: Trained using NVIDIA Tesla T4.
- **Loss Function**: Uses non-saturating GAN loss with R1 regularization.
- **Training Duration**: Depends on the dataset size and computing power.

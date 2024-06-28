# Image Colorization using Conditional GANs

This project explores and implements a state-of-the-art approach for automatic image recolorization using Conditional Generative Adversarial Networks (cGANs).

## Introduction
Image colorization is a significant task in computer vision, aiming to add color to grayscale images. This project leverages cGANs for image-to-image translation, particularly for recoloring grayscale images.

## Dataset
The project uses a dataset of grayscale images with their corresponding colored versions. The dataset is split into training and validation sets.

## Model Architecture
The architecture consists of a Generator and a Discriminator. The Generator uses a U-Net structure, and the Discriminator uses a PatchGAN architecture.

## Training
The model is trained using the cGAN framework. The Generator learns to produce realistic color images, while the Discriminator learns to distinguish between real and generated images.

## Results
The trained model can recolor grayscale images with high accuracy, preserving details and maintaining visual appeal.


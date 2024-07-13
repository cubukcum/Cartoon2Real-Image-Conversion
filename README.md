# Cartoon2Real-Image-Conversion
This project focuses on converting cartoonish images to realistic images using Generative Adversarial Networks (GANs). The implementation involves training a GAN model on a dataset of cartoonish drawings and their corresponding real photos, followed by evaluating the model's performance using both qualitative and quantitative metrics.

## Introduction
This project aims to transform non-realistic, cartoonish images into more realistic-looking images using GANs. The focus is on ensuring the generated images maintain high fidelity and realism.

## Dataset Exploration
The dataset consists of cartoonish drawings of people (grayscale) and real photos of people (RGB). Both image types are sized 200x250.

## Dataset Preprocessing
Images are preprocessed to normalize pixel values and resize to a consistent shape. Data augmentation techniques are applied to increase the diversity of the training.

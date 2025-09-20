# Image-to-Image Translation with cGAN (pix2pix)

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/) [![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)](https://www.tensorflow.org/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview
This project demonstrates image-to-image translation using a pre-trained conditional Generative Adversarial Network (cGAN) based on the pix2pix architecture. It leverages a model from TensorFlow Hub (noted as ESRGAN for super-resolution in the code, a specific application of image-to-image translation) to transform input images, such as enhancing resolution or applying conditional mappings. The implementation is in a Jupyter Notebook, allowing easy experimentation with different images and visualizations.

Pix2pix is a popular cGAN framework for paired image-to-image translation tasks, enabling applications like sketch-to-photo, day-to-night, or super-resolution. This project provides a simple, no-training-required entry point to explore GAN-based image generation.

## Problem Statement
Develop a system using a pre-trained conditional Generative Adversarial Network (cGAN) model, specifically pix2pix, to perform image-to-image translation tasks such as converting low-resolution images to high-resolution or applying style transfers. The implementation should load a model from TensorFlow Hub, process a user-provided input image, generate the translated output, and visualize both for comparison, showcasing the capabilities of GANs in conditional image generation without training from scratch.

## Features
- **Pre-trained Model Loading**: Uses TensorFlow Hub to load a ready-to-use pix2pix/ESRGAN model.
- **Image Processing**: Handles image loading, preprocessing, and generation.
- **Visualization**: Side-by-side comparison of input and generated images using Matplotlib.
- **Extensible**: Easily adaptable for other image-to-image tasks or custom datasets.
- **Dependencies**: Relies on TensorFlow, TensorFlow Hub, Matplotlib, NumPy, and PIL for image handling.

## Requirements
- Python 3.x
- Jupyter Notebook (or JupyterLab) for running the `.ipynb` file
- Required packages (installed via pip in the notebook):
  - tensorflow
  - tensorflow-hub
  - matplotlib
  - numpy (implicit via tensorflow)
  - pillow (for PIL)
  - requests (for potential URL-based image loading)

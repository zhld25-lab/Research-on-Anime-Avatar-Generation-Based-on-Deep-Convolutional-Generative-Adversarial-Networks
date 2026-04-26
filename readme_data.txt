Dataset Description

This folder contains the anime avatar image dataset used for training the DCGAN model.

Dataset source:
Heywhale public anime avatar dataset

Original dataset:
49,641 RGB anime avatar images, each with a resolution of 96 x 96 pixels.

Dataset used in this project:
2,500 selected anime avatar images were used for model training.

Image format:
RGB images in JPG/PNG format.

Usage:
The images in this folder are loaded by main.py and preprocessed before training.
The preprocessing steps include resizing images to 64 x 64 pixels, center cropping, converting images to tensors, and normalizing pixel values to the range [-1, 1].

Purpose:
This dataset is used to train a Deep Convolutional Generative Adversarial Network (DCGAN) to generate anime avatar images.

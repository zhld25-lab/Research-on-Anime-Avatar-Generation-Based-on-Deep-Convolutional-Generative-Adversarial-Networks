# Anime Avatar Generation Using DCGAN

## Project Goal
The goal of this project is to generate anime-style avatar images using a Deep Convolutional Generative Adversarial Network (DCGAN).

## Dataset
The model is trained on an anime face dataset containing 2500 RGB images with a resolution of 96×96 pixels. The images are resized to 64×64 and normalized before training.

## Model
The DCGAN architecture consists of a Generator and a Discriminator trained in an adversarial framework.

## Training
Optimizer: Adam  
Learning Rate: 0.0002  
Batch Size: 128  
Epochs: 50

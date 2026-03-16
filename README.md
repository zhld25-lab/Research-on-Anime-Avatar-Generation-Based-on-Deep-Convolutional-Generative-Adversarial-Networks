# Anime Avatar Generation Using DCGAN

## Project Goal
The goal of this project is to generate anime-style avatar images using a Deep Convolutional Generative Adversarial Network (DCGAN).
The model learns visual patterns from an anime face dataset and produces new synthetic images.

## Dataset
The model is trained on an anime face dataset containing 2500 RGB images with a resolution of 96×96 pixels. The images are resized to 64×64 and normalized before training.The model is trained on an anime face dataset. The dataset contains anime-style avatar images that are used to train the DCGAN model to learn the distribution of anime faces.

## Model
The DCGAN architecture consists of a Generator and a Discriminator trained in an adversarial framework.
Generator: generates anime faces from random noise.  
Discriminator: distinguishes between real and generated images.

## Training
Optimizer: Adam  
Learning Rate: 0.0002  
Batch Size: 128  
Epochs: 50

## Project Structure
Research-on-Anime-Avatar-Generation-Based-on-Deep-Convolutional-Generative-Adversarial-Networks/
├── README.md                     # Project description and documentation
├── code.ipynb                    # Jupyter notebook containing the DCGAN training code
├── dataset information.txt       # Description of the dataset used for training
├── anime_dcgan_checkpoint.pth    # Trained DCGAN model checkpoint
│
├── final_generated_faces.png     # Final generated anime avatar samples
├── generator_progression.png     # Visualization of generator progress during training
├── training_loss_curve.png       # Training loss curve for generator and discriminator

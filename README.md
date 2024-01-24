# Testing GANs for Image Generation with CIFAR-10 data

- This GAN is specifically designed for CIFAR-10 dataset which is a file that contains 60,000 of (32x32x3) color images in 10 different classes.
- The classes are: Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck.

## Overview
The goal of this project is to design (try out) the GANs for CIFAR-10 dataset and make it much more efficient to generate images based on samples photos. 

## Implementation Details

1. Imported data from the in-built Keras dataset.

2. Trained the Discriminator and Generator separately to evaluate their individual efficiencies.

3. Trained the composite model with 200 epochs and a batch size of 128 (64 real images, 64 fake images).

4. Summarized the performance of the Discriminator by evaluating its accuracy and the Generator by assessing the quality of the generated images.

**NOTE:** The model was trained for only 21 epochs.

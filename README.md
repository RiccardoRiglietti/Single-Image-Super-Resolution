# Single-Image-Super-Resolution

This project is based on replicating the paper "Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial
Network" [1] and trying to improve it by using a WGAN architecture. The goal is single image super resolution, which means upscaling an image from low resolution to high resolution using a deep CNN

## Dataset

The download link and set-up instructions for the dataset can be found at the start of the Colab Notebook.

## Results

Given the limited computational capacity of the free instance of Google Colab the CNN gives only limited improvements over a simple bicubic interpolation and the GANs training architectures do not improve the results because we did not have time to find the correct hyperparameteres (as GAN training is very sensitive to hyperparameters). Output images can be seen in the Colab Notebook.

## [Link to the Colab Notebook](https://colab.research.google.com/drive/1eJd3AWKTSNFvVlCSA4_Yu4CN3htFZbot?usp=sharing)

## Authors

Riccardo Riglietti, Luis Gustavo Cattelan, Antonio Scardino

## Bibliography

- [1]   https://arxiv.org/abs/1609.04802
- [2]   https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html 
- [3]   https://github.com/leftthomas/SRGAN
- [4]   https://medium.com/mlearning-ai/how-to-improve-image-generation-using-wasserstein-gan-1297f449ca75
- [5]   https://towardsdatascience.com/custom-dataset-in-pytorch-part-1-images-2df3152895




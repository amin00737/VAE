👗 Variational Autoencoder (VAE) on Fashion-MNIST

A clean implementation of a Variational Autoencoder (VAE) using TensorFlow/Keras to generate synthetic fashion images from the Fashion-MNIST dataset.

🔍 What This Project Does

Loads and preprocesses Fashion-MNIST (normalization + flattening)

Builds an Encoder that learns a latent Gaussian distribution

Implements the reparameterization trick

Builds a Decoder that reconstructs images from latent samples

Trains the VAE using:

Reconstruction loss (MSE)

KL divergence regularization

Generates new synthetic fashion images by sampling from the latent space

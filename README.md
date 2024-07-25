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


🧠 Model Architecture

Input dimension: 784 (28×28 flattened images)

Latent space dimension: 2

Hidden layer: 256 neurons (ReLU)

Optimizer: Adam

Loss: Reconstruction + KL divergence

🎯 Outcome

After training, the decoder can generate new fashion-like images by sampling points from a 2D latent space.
The structured latent representation enables smooth interpolation between generated samples.

📦 Requirements

TensorFlow / Keras

NumPy

Matplotlib
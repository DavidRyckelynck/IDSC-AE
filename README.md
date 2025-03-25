# IDSC-AE

Convolutional Autoencoder

Sticking with mechanical predictions, let's improve our autoencoder's performance using convolutional layers. We'll build a convolutional autoencoder to compress the dataset.

    The encoder portion will be made of convolutional layers and the decoder will be made of transpose convolutional layers that learn to "upsample" a compressed representation.

Compressed Representation

A compressed representation can be great to learn a latent space. In practice, the compressed representation often holds key information about an input image and we can use it for denoising images or model ordre reduction!

Let's get started by importing our libraries and getting the dataset.

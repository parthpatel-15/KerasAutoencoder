# KerasAutoencoder
This repository showcases examples of autoencoders implemented using Keras. Autoencoders are neural networks designed for unsupervised learning and are particularly effective in tasks like image reconstruction and denoising. 

# Simple Autoencoder:
- Objective: Implement a basic autoencoder to reconstruct images from the MNIST dataset.
- Architecture:
    + Input Layer: 784 neurons (flattened image size).
    +  Encoding Layer: 128 neurons, ReLU activation.
    +  Code Layer: 16 neurons, ReLU activation.
    +  Ecoding Layer: 128 neurons, ReLU activation.
    +  Output Layer: 784 neurons, Sigmoid activation.

- Steps:
Load and preprocess the MNIST dataset.
Build an autoencoder architecture with an input layer, encoding layer, decoding layer, and output layer.
Compile and train the autoencoder using binary crossentropy loss.
Evaluate the trained autoencoder on the test set and visualize original and decoded images.

- Output: 
<img width="1298" alt="Screenshot 2024-01-11 at 12 09 23 AM" src="https://github.com/parthpatel-15/KerasAutoencoder/assets/79576096/7c3461ee-3ad1-425b-84fc-52ccfda301f4">


# Denoising Autoencoder:
- Objective: Enhance the robustness of the autoencoder by training it to denoise images with added random noise.
- Architecture: 
  + Similar to the simple autoencoder.

- Steps:
Introduce random noise to the training and test sets.
Clip the noisy images to maintain pixel values between 0 and 1.
Build and train a denoising autoencoder similar to the simple autoencoder.
Evaluate the denoising autoencoder on the noisy test set and visualize original, noisy, and decoded images.

- Output: 
<img width="1329" alt="Screenshot 2024-01-11 at 12 12 08 AM" src="https://github.com/parthpatel-15/KerasAutoencoder/assets/79576096/71c0a676-8f91-43fd-9e53-bbc9fbc82262">


# De-noising-Autoencoder

One of the major applications of autoencoder is to denoise images quite successfully just by training the network on noisy images.

Let us add some noise to MNIST images and feed these noisy images to our model. The model will produce reconstructed images based on the noisy input. But, we want it to produce normal un-noisy images, and so, when we calculate the loss, we will still compare the reconstructed outputs to the original images!

![alt text](https://github.com/Yogesh-S/27-De-noising-Convolutional-Autoencoder/blob/main/autoencoder_denoise.png?raw=true)

# Schematic of the network

![alt text](https://github.com/Yogesh-S/27-De-noising-Convolutional-Autoencoder/blob/main/conv_enc_3.JPG?raw=true)

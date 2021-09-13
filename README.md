# generative-adversarial-network-gan
Intro to Generative Adversarial Network (GAN) projects.
A good reading material for GAN: https://towardsdatascience.com/understanding-generative-adversarial-networks-gans-cd6e4651a29

# 1. How GANs work?

Generator vs Discriminator:

![alt text][logo]

[logo]: https://miro.medium.com/max/1400/1*nAVqFluPijpBWR2tI4gCxg.png "Logo Title Text 1"

The big picture: GANs are able to generate new images by training two competing algorithms (a generator and a discriminator simultaneously)

GAN Process:

* The generator creates images that look like the training input data
* The discriminator spots whether it is real (the training data) or fake (the generator's output)
* The generator and discriminator both improve during training with feedback from each other.
* Repeat until both the friendly competition between the generator and discriminator reaches an equilibrium:
neither player can improve further

# 2. GAN variants
* DCGAN
* WGAN & WGAN-GP
* cGAN
* Pix2Pix
* CycleGAN

# 3. GAN applications

GANS can be used in many applications, from image/audio/video synthesis, style transfer, to colorization --your imagination is your limit.

* Synthesis
* Style Transfer
* Inpainting
* Uncropping
* Colorization



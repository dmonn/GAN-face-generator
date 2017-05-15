# Generating faces using GANs

This project was done as part of Udacity's DLFND. In this project, it should be possible to generate faces using the CelebA dataset. The GAN was tested on the MNIST dataset.

## Architecture

The architecture was chosen as described in the initial DCGAN research paper "Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks”.

![dcgan architecture](https://cdn-images-1.medium.com/max/1000/1*39Nnni_nhPDaLu9AnTLoWw.png "DCGAN Architecture")

## Result

The network was first trained on the MNIST dataset. After being able to generate new handwritten digits, the CelebA dataset was used. The network then run for one full epoch and produced this result.

![generation result](https://cdn-images-1.medium.com/max/1600/1*OsemoFk6aglaGleBWI6VPA.png "result")

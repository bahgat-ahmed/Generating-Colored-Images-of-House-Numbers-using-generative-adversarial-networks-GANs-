# Generating Colored Images of House Numbers using Generative Adversarial Networks (GANs)

This is one of the projects I've built in Udacity **Deep Learning Nanodegree**.

A lot of this readme is taken exactly from the project description made by Udacity and I have just made small modifications to their description and put it in this readme.

![](assets/svhn_dcgan.png)

## Deep Convolutional GANs
In this notebook, I've built a GAN using convolutional layers in the generator and discriminator. This is called a Deep Convolutional GAN, or DCGAN for short. The DCGAN architecture was first explored in 2016 and has seen impressive results in generating new images; you can read the [original paper, here](https://arxiv.org/pdf/1511.06434.pdf).

I've been training DCGAN on the [Street View House Numbers](http://ufldl.stanford.edu/housenumbers/) (SVHN) dataset. These are color images of house numbers collected from Google street view. SVHN images are in color and much more variable than MNIST dataset.

So, my goal was to create a DCGAN that can generate new, realistic-looking images of house numbers. 

## The project steps
1. Loading in and pre-processing the house numbers dataset
2. Defining discriminator and generator networks
3. Training these adversarial networks
4. Visualizing the loss over time and some sample, generated images

>More instructions and details are written in the Notebook.

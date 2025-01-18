# Cifar10-Image-Separation
This Notebook as a part of the Deep Learning course at University of Bologna(UniBo).
The model takes as input an image created by averaging two random samples from CIFAR-10 and is tasked with predicting the categories of the two components.
The first image belongs to the first five categories (airplane, automobile, bird, cat, deer), while the second belongs to the remaining categories (dog, frog, horse, ship, truck). The model must return two labels, each within a range of five possible values.

The evaluation metric for the model is as follows: calculate the classification accuracy for the two component images and then compute their average.

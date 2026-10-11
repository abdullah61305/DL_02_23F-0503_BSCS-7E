# Deep Learning Assignment 2

This repository contains my Deep Learning Assignment 2 notebook (Roll Number 23F-0503, BSCS Section 7E). It covers CIFAR-10 image classification with only 500 training images, using a small CNN with an Inception-style module, data augmentation, regularisation, an ablation study, error analysis and test-time augmentation.

The notebook includes the code and the existing outputs of the experiments.

To reproduce the results, open `DL_ASS02_23F_0503.ipynb` in Google Colab, select a T4 GPU runtime and run all cells. The notebook downloads CIFAR-10 through torchvision, and all seeds are fixed in the code (data split seed 42, test corruption seed 2026, training seeds 0, 1 and 2).

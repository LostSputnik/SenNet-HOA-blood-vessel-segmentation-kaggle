# Hello!

This is my repo for kaggle's [SenNet + HOA - Hacking the Human Vasculature in 3D](https://www.kaggle.com/competitions/blood-vessel-segmentation) competition.

> Note: repo is WIP

Given the challenges of the competition, i wrote [this](sennet-hoa-3d-training-monai-pytorch.ipynb) public notebook, particularly to integrate MONAI library of 3D models in order to train on more robust and diverse set of architectures. Currently a bronze 🥉 notebook in [kaggle](https://www.kaggle.com/code/tahseenislamsajon/sennet-hoa-3d-training-monai-pytorch), it,

- Generates 3D volumes from the continuos 2D slices
- Performs volumetric augmentations
- Trains a MONAI UNETR model on the data.

There's much more insight i have to share from the competiton. Hopefully will get to it very soon! PRs and recommendations are very much welcome ^\_^

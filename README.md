# 2d-nerf-model-pytorch

# Introduction
This repository contains the implementation of a 2D NERF (Neural Radiance Fields) model for image rendering using PyTorch in a Jupyter Notebook format. The model is designed to render images using a 9-layer Multi-Layer Perceptron (MLP) and sinusoidal position encoding (PE).

# Model Configuration
The model is configured with the following hyperparameters:

image_size: 100
n_layers: 9
layer_units: 256
epochs: 200
lr: 0.00001
encoding_degree: 5
batch_size: 32
up_scale: 4
momentum: 0.5


Requirements
PyTorch >= 1.7

# Getting Started

Open the Jupyter Notebook 2d-nerf-model-implementation.ipynb and follow the instructions to train the model on your own dataset.


Contributions are welcome! Please feel free to submit a pull request or open an issue for any bug fixes or new features.

License
This project is licensed under the MIT License.

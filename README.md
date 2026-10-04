# mnist-pytorch-mlp
MNIST handwritten digit classification using PyTorch
# MNIST Classification with PyTorch

A simple MNIST handwritten digit classification project using PyTorch.

## Model

MLP architecture:

`784 → 100 → 50 → 10`

* Activation: ReLU
* Loss: Cross Entropy Loss
* Optimizer: SGD
* Learning rate: 0.01
* Batch size: 64
* Epochs: 20

## Evaluation

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score

## Files

```text
notebooks/
└── MNIST_MLP.ipynb
```

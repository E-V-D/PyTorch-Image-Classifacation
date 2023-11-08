# PyTorch-Image-Classifacation

import torch
import torchvision

train_data = torchvision.datasets.FashionMNIST(root='data', train=True, 
download=True, transform=torchvision.transforms.ToTensor(), target_transform=None)

test_data = torchvision.datasets.FashionMNIST(root='data', train=False, 
download=True, transform=torchvision.transforms.ToTensor(), target_transform=None)


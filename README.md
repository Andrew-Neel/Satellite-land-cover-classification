# Land-Cover Classification Using Deep Learning and Transfer Learning
## Project Overview

This project investigates the use of deep learning for land-cover classification using the EuroSAT satellite imagery dataset. The primary objective is to compare the performance of a Convolutional Neural Network (CNN) trained from scratch with a ResNet-50 transfer learning model. By evaluating both approaches, the project examines whether pretrained visual feature representations can improve classification accuracy for remote sensing imagery.

## Research Question

How does transfer learning using ResNet-50 compare to a convolutional neural network trained from scratch for land-cover classification on the EuroSAT dataset?

## Dataset

The project uses the [EuroSAT](https://github.com/phelber/EuroSAT) dataset, which contains approximately 27,000 RGB satellite images derived from Sentinel-2 satellite imagery. The dataset is organized into 10 land-cover categories:

AnnualCrop
Forest
HerbaceousVegetation
Highway
Industrial
Pasture
PermanentCrop
Residential
River
SeaLake

The dataset was split into training and validation sets using an 80/20 ratio.

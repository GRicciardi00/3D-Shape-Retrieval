# 3D-Shape-Retrieval
## Overview
This repository contains the work for a 3D Shape Retrieval project. The goal of this project is to implement a system capable of retrieving 3D shapes using view-based descriptors. It leverages the trimesh library for handling 3D mesh data and PyTorch for the construction and training of a neural network model designed for the task.
## Dataset
The project utilizes the McGill dataset, which comprises 10 classes of different 3D models with articulating parts. The dataset includes mesh representations in .ply format, corresponding to the boundary voxels of the voxel representations. A detailed explanation of the data collection, preprocessing, and splitting process is provided, ensuring a structured approach to model training and evaluation.
## Model Architecture
The neural network model of choice is GoogleNet, selected for its inception modules that capture features at varying scales and its deep architecture supplemented with auxiliary classifiers to aid training. The model incorporates techniques to mitigate overfitting and improve computational efficiency, such as global average pooling and the use of 1x1 convolutions.
## Libraries
- trimesh
- PyTorch
- NumPy
- Matplotlib
- scikit-learn
- PIL
- torchvision

## Result
![alt text](https://github.com/GRicciardi00/3D-Shape-Retrieval/blob/main/result.png)

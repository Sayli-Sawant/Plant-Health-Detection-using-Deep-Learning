# Plant Health Detection & PCA Implementation

## Project Overview

This repository contains two key projects:

1. **Plant Health Detection Using Deep Learning**: This project aims to detect plant health status by employing deep learning techniques such as DenseNet for classification and U-Net for segmentation. The model effectively identifies unhealthy plants and highlights affected areas using image masks.
   
2. **PCA Implementation from Scratch**: This project involves the development of a Principal Component Analysis (PCA) algorithm from scratch, focusing on dimensionality reduction for high-dimensional datasets. The PCA implementation uses eigenvalue decomposition to reduce the number of features while retaining maximum variance in the data.

## Dataset

The datset has two folders, train and test. You can access the datset via the following link:

[Dataset](https://indianinstituteofscience-my.sharepoint.com/:f:/g/personal/saylisantosh_iisc_ac_in/ErpVflzO6o5JnIaE17F0NVABhSbPhHNcsbsEGzryLQwjzw?e=J8Brws)

Along with this I have uploaded the train.csv file, which contains the image names along with their binary predictions and segmentation prediction(RLE masks).

The output file created will also be in the same format.


## Methods & Techniques

### Plant Health Detection
- **Model**: DenseNet for classification, U-Net for segmentation.
- **Data**: Plant images with corresponding segmentation masks.
- **Goal**: Classify plants as healthy or unhealthy and accurately segment affected regions.

### PCA Implementation
- **Algorithm**: Eigenvalue decomposition for dimensionality reduction.
- **Goal**: Reduce dataset dimensions while preserving as much variance as possible.
- **Implementation**: PCA was implemented without using external libraries for educational purposes.

## Libraries Used

- **TensorFlow/Keras**: For building and training DenseNet and U-Net models.
- **NumPy**: For matrix operations and eigenvalue decomposition in the PCA project.
- **OpenCV/PIL**: For image processing tasks in plant health detection.

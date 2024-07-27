<img src="digit classifiation.png" alt="Alt text" width="800" />

# Digit-Classification-Using-KNN-From-Scratch
we aim to classify digits ranging from 0 to 9 using the MNIST dataset.
# Digit Classification Using KNN From Scratch

## Overview

In this project, we aim to classify digits ranging from 0 to 9 using the K-Nearest Neighbors (KNN) algorithm implemented from scratch. KNN is a simple yet effective classification method that relies on the similarity of data points.

## Dataset

We utilized the MNIST dataset, a well-known benchmark dataset in machine learning and computer vision. It consists of 28x28 pixel grayscale images of handwritten digits (0-9) along with their corresponding labels.

## Implementation

Our implementation directly applies the KNN algorithm to the MNIST dataset:
- **Feature Extraction:** Each image is flattened into a vector of pixel intensities.
- **Distance Calculation:** Euclidean distance is used to measure similarity between images.
- **Classification:** For each test image, the algorithm finds the K nearest neighbors in the training set and assigns the label based on majority voting.
  
We achieved an accuracy of 96.87% on the test set, demonstrating the effectiveness of our approach in digit classification.

## Repository Structure

- **data/:** Directory containing the MNIST dataset.
- **knn_mnist_data_tuhin_patra_version_no1.ipynb:** Jupyter Notebook containing the code for implementing KNN algorithm and digit classification.

## Running the Notebook

To run the notebook:
1. Ensure Python and Jupyter Notebook are installed.
2. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Digit-Classification-KNN-From-Scratch.git
   cd Digit-Classification-KNN-From-Scratch

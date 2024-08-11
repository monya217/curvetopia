# Curvetopia
# Shape Regularization and Classification

## Overview

This project addresses the problem of regularizing imperfect, hand-drawn geometric shapes. By first classifying the shapes, we can then replace them with their ideal, regularized versions. The solution is implemented using a Convolutional Neural Network (CNN) in a Jupyter Notebook.

## Problem Statement

Hand-drawn or imperfect geometric shapes often exhibit distortions, rotations, or other irregularities, making them unsuitable for applications requiring precise geometric forms. The goal of this project is to classify these imperfect shapes and automatically replace them with their regularized counterparts.

## Solution

The solution consists of the following steps:

1. **Shape Generation**: Creating a dataset of geometric shapes with imperfections and random rotations to simulate real-world conditions.
2. **Data Augmentation**: Enhancing the dataset with real-time data augmentation techniques.
3. **Model Training**: Training a CNN to accurately classify the shapes despite distortions.
4. **Shape Regularization**: Once classified, the imperfect shapes are replaced with their ideal, regular versions.

## Getting Started

### Prerequisites

Ensure the following packages are installed:

- Python 3.x
- Jupyter Notebook
- TensorFlow
- NumPy
- Matplotlib
- Pillow

Install the required packages using pip:

```bash
pip install tensorflow numpy matplotlib pillow
```
### Running the Notebook

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/shape-regularization.git
    cd shape-regularization
    ```

2. **Open the Jupyter Notebook**:
    Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

    In the Jupyter Notebook interface, navigate to and open the `shape_regularization.ipynb` file.

3. **Execute the Cells**:
    Follow the instructions provided in the notebook to generate shapes, train the model, and perform shape regularization.

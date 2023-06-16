# Handwritten_Digits_Classifier
A neural network-based approach for handwritten digit classification using the MNIST dataset. Explore different models, techniques, and architectures to achieve accurate digit recognition.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models](#models)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Introduction
In this project, we aim to classify handwritten digits by training various neural network models. We begin with a simple network without hidden layers and gradually introduce more complex architectures such as models with hidden layers, a flatten layer, and a convolutional neural network (CNN). By comparing the performance of these models, we gain insights into their effectiveness for digit recognition.

## Dataset
The MNIST dataset, a widely used benchmark dataset for digit recognition, is used in this project. It consists of 60,000 training images and 10,000 testing images, each representing a grayscale image of size 28x28 pixels. The images are labeled with the corresponding digits ranging from 0 to 9. Prior to training the models, the pixel values are normalized between 0 and 1.

## Models
The following models are implemented and compared in this project:
- No Hidden Layer: A simple neural network with only input and output layers.
- Hidden Layer: A neural network with a hidden layer for improved performance.
- Flatten Layer: A model utilizing the flatten layer to avoid explicit reshaping of the input dataset.
- CNN (Convolutional Neural Network): A model employing convolutional and pooling layers for digit recognition.

## Getting Started
To get started with this project, follow these steps:
1. Clone the repository: `git clone <repository-url>`
2. Install the necessary dependencies: `pip install -r requirements.txt`
3. Explore the Jupyter Notebook: `Handwritten_Digits_Classifier.ipynb`
4. Run the notebook cells to train and evaluate the models.

## Contributing
Contributions to this project are welcome! If you have any ideas, improvements, or bug fixes, please submit a pull request or open an issue.

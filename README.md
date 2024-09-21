# Human Activity Recognition using Neural Networks, Gaussian Naive Bayes, and Softmax Regression

## Overview
This project focuses on the development of a Human Activity Recognition (HAR) system using a combination of custom Neural Networks, Gaussian Naive Bayes, and Softmax Regression. The objective is to classify human activities from sensor data, achieving high accuracy while balancing computational efficiency.

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Data Description](#data-description)
- [Modeling Approach](#modeling-approach)
  - [Neural Networks](#neural-networks)
  - [Gaussian Naive Bayes](#gaussian-naive-bayes)
  - [Softmax Regression](#softmax-regression)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Project Structure
The repository contains the following files:
- `HumanActivityRecognition_HTM.html`: Detailed HTML report of the project analysis and results.
- `HumanActivityRecognition_Ipynb.ipynb`: Jupyter notebook with the code for data preprocessing, model training, and evaluation.

## Data Description
The dataset consists of sensor data collected from accelerometers and gyroscopes in smartphones. Each sample corresponds to a specific human activity, such as walking, sitting, or standing. The data is preprocessed to extract meaningful features, which are then used to train the machine learning models.

## Modeling Approach

### Neural Networks
A custom neural network architecture was designed to capture complex patterns in the sensor data. The network includes multiple hidden layers with ReLU activations, followed by a Softmax output layer for classification.

### Gaussian Naive Bayes
Gaussian Naive Bayes is used as a baseline classifier. It assumes the features follow a Gaussian distribution and computes posterior probabilities for classification.

### Softmax Regression
Softmax Regression, a generalization of logistic regression for multi-class classification, is applied as a comparison point to evaluate the performance against the neural network.

## Installation
To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/HumanActivityRecognition.git
   cd HumanActivityRecognition

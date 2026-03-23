# MLP MNIST Tutorial

## Overview
This project demonstrates the implementation of a Multilayer Perceptron (MLP) for image classification using the MNIST dataset. Multiple experiments are conducted to analyze the effect of different parameters.

## Features
- Neural Network implementation using TensorFlow
- Multiple experiments (depth, activation, optimizer, dropout)
- Accuracy and loss visualization
- Confusion matrix analysis
- Prediction visualization

## Experiments
1. Baseline Model
2. Deep Network
3. Tanh Activation
4. SGD Optimizer
5. Dropout Regularization

## Results

| Experiment | Accuracy | Time (sec) |
|----------|---------|------------|
| Baseline | 0.9709 | 9.13 |
| Deep Network | 0.9770 | 12.34 |
| Tanh | 0.9733 | 9.62 |
| SGD | 0.9459 | 9.46 |
| Dropout | 0.9714 | 10.33 |

## Installation

```bash
pip install tensorflow matplotlib numpy pandas scikit-learn
```

## Run Project
jupyter notebook

## Project structure
├── main.ipynb

├── Assignment_01_Report.pdf

├── README.md

├── requirements.txt

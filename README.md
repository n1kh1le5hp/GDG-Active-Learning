# GDG Active Learning Project

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=yellow)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-red?logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-1.24%2B-orange?logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-purple?logo=pandas&logoColor=white)
![GDG](https://img.shields.io/badge/GDG-IIT%20Kanpur-green)

A comprehensive collection of machine learning assignments from Google Developer's Group Active Learning program at IIT Kanpur

---

## Overview

This repository contains three comprehensive assignments completed as part of the GDG Active Learning program at IIT Kanpur. The project progresses from Python fundamentals and data analysis to advanced deep learning and active learning techniques, demonstrating proficiency in the complete machine learning pipeline.

## What You'll Find

### Assignment 1: Python Foundations & Data Analysis

A thorough exploration of Python programming and data manipulation fundamentals:

- **Control Flow & Algorithms**: Fibonacci sequence generation and iterative algorithms
- **Data Structures**: List comprehensions, dictionary operations, and efficient data handling
- **Numerical Computing**: NumPy array operations, matrix manipulation, and statistical analysis
- **Data Analysis**: Pandas DataFrame operations, filtering, merging, and aggregation
- **Real-world Dataset Analysis**: Exploratory data analysis on the Titanic dataset
- **Statistical Operations**: Mean, median, standard deviation, and Z-score normalization
- **Data Visualization**: Line plots, bar charts, and scatter plots using Matplotlib and Seaborn

**Key Topics Covered**:
```python
- File I/O and CSV processing
- NumPy broadcasting and advanced indexing
- Pandas groupby operations and data transformation
- Missing value imputation strategies
- Statistical visualization and interpretation
```

### Assignment 2: Deep Learning with CNNs

Implementation of a Convolutional Neural Network for image classification:

**Architecture**:
- 2 Convolutional Layers with ReLU activation
- Max Pooling for spatial dimensionality reduction
- Fully Connected Layers for classification
- Adam optimizer with Cross-Entropy Loss

**Results**:
- **Dataset**: MNIST (60,000 training, 10,000 test samples)
- **Test Accuracy**: 99.02%
- **Training**: 10 epochs with batch size 64
- **Framework**: PyTorch with CUDA acceleration

### Assignment 3: Advanced Active Learning

Advanced implementation incorporating uncertainty sampling and diversity metrics:

**Active Learning Techniques**:

1. **Uncertainty Metrics**
   - Least Confidence Sampling
   - Prediction Entropy
   - Margin Sampling

2. **Diversity Metrics**
   - Cosine Similarity
   - L2 Norm Distance
   - Feature Space Clustering

3. **Information Theory**
   - KL Divergence for sample selection
   - Neighbor-based probability distributions

**Performance**:
- **Test Accuracy**: 99.07%
- Successfully integrated multiple active learning strategies
- Comprehensive metric analysis and interpretation

## Getting Started

### Prerequisites

```bash
pip install torch torchvision numpy pandas matplotlib seaborn scikit-learn
```

### Running the Notebooks

**1. Assignment 1 - Data Analysis Fundamentals**
```bash
cd Assignment_1/
jupyter notebook Nikhilesh_Active_Learning_Assignment_1.ipynb
```

**2. Assignment 2 - CNN Implementation**
```bash
jupyter notebook Nikhilesh_Active_Learning_Assignment_2.ipynb
```

**3. Assignment 3 - Active Learning**
```bash
jupyter notebook Nikhilesh_Active_Learning_Assignment_3.ipynb
```

## Key Achievements

- ✅ 99.07% accuracy on MNIST test set using custom CNN
- ✅ Implemented 6 different active learning metrics for intelligent sample selection
- ✅ Processed real-world datasets (Titanic, Iris) with comprehensive EDA
- ✅ Created 15+ visualization examples covering various plot types
- ✅ Developed modular, reusable code following best practices

## Technical Stack

| Category | Technologies |
|----------|--------------|
| **Programming** | Python 3.8+ |
| **Deep Learning** | PyTorch 2.0+, torchvision |
| **Data Analysis** | NumPy, Pandas |
| **Visualization** | Matplotlib, Seaborn |
| **Machine Learning** | Scikit-learn |
| **Development** | Jupyter Notebooks |
| **Hardware** | CUDA-enabled GPU |

## Project Structure

```
GDG-Active-Learning/
├── Assignment_1/
│   ├── Nikhilesh_Active_Learning_Assignment_1.ipynb
│   └── Titanic-Dataset.csv
├── Nikhilesh_Active_Learning_Assignment_2.ipynb
├── Nikhilesh_Active_Learning_Assignment_3.ipynb
└── README.md
```

## Learning Outcomes

Through this project, I gained expertise in:

1. **Python Programming**: Advanced features, data structures, and algorithmic thinking
2. **Data Analysis**: Cleaning, transforming, and analyzing real-world datasets
3. **Deep Learning**: Building and training neural networks from scratch
4. **Active Learning**: Implementing intelligent data selection strategies
5. **Statistical Analysis**: Understanding distributions, normalization, and metrics
6. **Data Visualization**: Creating informative and publication-ready plots
7. **Software Engineering**: Writing clean, documented, and reproducible code

## Context

This project was completed as part of the Google Developer's Group (GDG) Active Learning program at IIT Kanpur. The program focused on practical machine learning applications, progressing from foundational concepts to advanced techniques.

## Related Concepts

- **Supervised Learning**: Classification tasks with labeled data
- **Convolutional Neural Networks**: Image recognition architectures
- **Active Learning**: Strategies for selecting informative training samples
- **Uncertainty Sampling**: Querying model uncertain predictions
- **Diversity Sampling**: Ensuring representative sample selection
- **Transfer Learning**: Adapting pre-trained models

---

<div align="center">

Completed during GDG Active Learning Program at IIT Kanpur

</div>

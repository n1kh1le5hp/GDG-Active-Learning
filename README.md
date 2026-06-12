+# GDG Active Learning Project
        2 +
        3 +<div align="center">
        4 +
        5 +![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=yellow)
        6 +![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-red?logo=pytorch&logoColor=white)
        7 +![NumPy](https://img.shields.io/badge/NumPy-1.24%2B-orange?logo=numpy&logoColor=white)
        8 +![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-purple?logo=pandas&logoColor=white)
        9 +![GDG](https://img.shields.io/badge/GDG-IIT%20Kanpur-green)
       10 +
       11 +*A comprehensive collection of machine learning assignments from Google Developer's Group Active Learning program a
          +t IIT Kanpur*
       12 +
       13 +</div>
       14 +
       15 +##  Overview
       16 +
       17 +This repository contains three comprehensive assignments completed as part of the GDG Active Learning program at II
          +T Kanpur. The project progresses from Python fundamentals and data analysis to advanced deep learning and active le
          +arning techniques, demonstrating proficiency in the complete machine learning pipeline.
       18 +
       19 +##  What You'll Find
       20 +
       21 +### Assignment 1: Python Foundations & Data Analysis
       22 +A thorough exploration of Python programming and data manipulation fundamentals:
       23 +
       24 +- **Control Flow & Algorithms**: Fibonacci sequence generation and iterative algorithms
       25 +- **Data Structures**: List comprehensions, dictionary operations, and efficient data handling
       26 +- **Numerical Computing**: NumPy array operations, matrix manipulation, and statistical analysis
       27 +- **Data Analysis**: Pandas DataFrame operations, filtering, merging, and aggregation
       28 +- **Real-world Dataset Analysis**: Exploratory data analysis on the Titanic dataset
       29 +- **Statistical Operations**: Mean, median, standard deviation, and Z-score normalization
       30 +- **Data Visualization**: Line plots, bar charts, and scatter plots using Matplotlib and Seaborn
       31 +
       32 +**Key Topics Covered:**
       33 +```python
       34 +- File I/O and CSV processing
       35 +- NumPy broadcasting and advanced indexing
       36 +- Pandas groupby operations and data transformation
       37 +- Missing value imputation strategies
       38 +- Statistical visualization and interpretation
       39 +```
       40 +
       41 +### Assignment 2: Deep Learning with CNNs
       42 +Implementation of a Convolutional Neural Network for image classification:
       43 +
       44 +**Architecture:**
       45 +- 2 Convolutional Layers with ReLU activation
       46 +- Max Pooling for spatial dimensionality reduction
       47 +- Fully Connected Layers for classification
       48 +- Adam optimizer with Cross-Entropy Loss
       49 +
       50 +**Results:**
       51 +- **Dataset**: MNIST (60,000 training, 10,000 test samples)
       52 +- **Test Accuracy**: 99.02%
       53 +- **Training**: 10 epochs with batch size 64
       54 +- **Framework**: PyTorch with CUDA acceleration
       55 +
       56 +### Assignment 3: Advanced Active Learning
       57 +Advanced implementation incorporating uncertainty sampling and diversity metrics:
       58 +
       59 +**Active Learning Techniques:**
       60 +1. **Uncertainty Metrics**
       61 +   - Least Confidence Sampling
       62 +   - Prediction Entropy
       63 +   - Margin Sampling
       64 +
       65 +2. **Diversity Metrics**
       66 +   - Cosine Similarity
       67 +   - L2 Norm Distance
       68 +   - Feature Space Clustering
       69 +
       70 +3. **Information Theory**
       71 +   - KL Divergence for sample selection
       72 +   - Neighbor-based probability distributions
       73 +
       74 +**Performance:**
       75 +- **Test Accuracy**: 99.07%
       76 +- Successfully integrated multiple active learning strategies
       77 +- Comprehensive metric analysis and interpretation
       78 +
       79 +##  Getting Started
       80 +
       81 +### Prerequisites
       82 +```bash
       83 +pip install torch torchvision numpy pandas matplotlib seaborn scikit-learn
       84 +```
       85 +
       86 +### Running the Notebooks
       87 +
       88 +1. **Assignment 1** - Data Analysis Fundamentals
       89 +   ```bash
       90 +   cd Assignment_1/
       91 +   jupyter notebook Nikhilesh_Active_Learning_Assignment_1.ipynb
       92 +   ```
       93 +
       94 +2. **Assignment 2** - CNN Implementation
       95 +   ```bash
       96 +   jupyter notebook Nikhilesh_Active_Learning_Assignment_2.ipynb
       97 +   ```
       98 +
       99 +3. **Assignment 3** - Active Learning
      100 +   ```bash
      101 +   jupyter notebook Nikhilesh_Active_Learning_Assignment_3.ipynb
      102 +   ```
      103 +
      104 +## Key Achievements
      105 +
      106 +-  **99.07% accuracy** on MNIST test set using custom CNN
      107 +-  Implemented **6 different active learning metrics** for intelligent sample selection
      108 +-  Processed **real-world datasets** (Titanic, Iris) with comprehensive EDA
      109 +-  Created **15+ visualization examples** covering various plot types
      110 +-  Developed **modular, reusable code** following best practices
      111 +
      112 +## 🛠️ Technical Stack
      113 +
      114 +| Category | Technologies |
      115 +|----------|--------------|
      116 +| **Programming** | Python 3.8+ |
      117 +| **Deep Learning** | PyTorch 2.0+, torchvision |
      118 +| **Data Analysis** | NumPy, Pandas |
      119 +| **Visualization** | Matplotlib, Seaborn |
      120 +| **Machine Learning** | Scikit-learn |
      121 +| **Development** | Jupyter Notebooks |
      122 +| **Hardware** | CUDA-enabled GPU |
      123 +
      124 +##  Project Structure
      125 +
      126 +```
      127 +GDG-Active-Learning/
      128 +├── Assignment_1/
      129 +│   ├── Nikhilesh_Active_Learning_Assignment_1.ipynb
      130 +│   └── Titanic-Dataset.csv
      131 +├── Nikhilesh_Active_Learning_Assignment_2.ipynb
      132 +├── Nikhilesh_Active_Learning_Assignment_3.ipynb
      133 +└── README.md
      134 +```
      135 +
      136 +##  Learning Outcomes
      137 +
      138 +Through this project, I gained expertise in:
      139 +
      140 +1. **Python Programming**: Advanced features, data structures, and algorithmic thinking
      141 +2. **Data Analysis**: Cleaning, transforming, and analyzing real-world datasets
      142 +3. **Deep Learning**: Building and training neural networks from scratch
      143 +4. **Active Learning**: Implementing intelligent data selection strategies
      144 +5. **Statistical Analysis**: Understanding distributions, normalization, and metrics
      145 +6. **Data Visualization**: Creating informative and publication-ready plots
      146 +7. **Software Engineering**: Writing clean, documented, and reproducible code
      147 +
      148 +##  Context
      149 +
      150 +This project was completed as part of the **Google Developer's Group (GDG) Active Learning program** at **IIT Kanpu
          +r**. The program focused on practical machine learning applications,
          + progressing from foundational concepts to advanced techniques.
      151 +
      152 +##  Related Concepts
      153 +
      154 +- **Supervised Learning**: Classification tasks with labeled data
      155 +- **Convolutional Neural Networks**: Image recognition architectures
      156 +- **Active Learning**: Strategies for selecting informative training samples
      157 +- **Uncertainty Sampling**: Querying model uncertain predictions
      158 +- **Diversity Sampling**: Ensuring representative sample selection
      159 +- **Transfer Learning**: Adapting pre-trained models
      160 +
      161 
      168 +
      169 +---
      170 +
      171 +<div align="center">
      172 +
      173 +**Built with ❤️ during GDG Active Learning Program at IIT Kanpur**
      174 +
      175 +</div>

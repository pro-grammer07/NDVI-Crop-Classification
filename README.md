# 🌾 NDVI-Based Rice and Cotton Crop Classification Using Machine Learning

> **An end-to-end machine learning pipeline for crop classification using multi-temporal NDVI data, advanced preprocessing, feature engineering, supervised learning, unsupervised learning, and comprehensive performance evaluation.**

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-success)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-red)
![Remote Sensing](https://img.shields.io/badge/Remote-Sensing-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

# 📖 Project Overview

Accurate crop identification is fundamental to modern precision agriculture, food security, yield forecasting, and sustainable land management. Traditional field surveys are labor-intensive, expensive, and difficult to scale across large agricultural regions.

This project presents a comprehensive **Machine Learning framework** for classifying **Rice** and **Cotton** crops using **Normalized Difference Vegetation Index (NDVI)** time-series data derived from satellite observations.

Rather than relying on a single observation, the model learns seasonal vegetation patterns across multiple time intervals, enabling accurate discrimination between crop types based on their growth behavior.

The project encompasses the complete machine learning lifecycle—from exploratory data analysis and preprocessing to model development, clustering, hyperparameter optimization, and performance evaluation.

---

# 🎯 Objectives

The primary goals of this project are to:

* Develop an automated crop classification system using NDVI time-series data.
* Analyze vegetation dynamics throughout the crop growth cycle.
* Perform extensive exploratory data analysis.
* Address data quality and class imbalance challenges.
* Compare multiple machine learning algorithms.
* Investigate clustering techniques for pattern discovery.
* Evaluate model performance using comprehensive statistical metrics.

---

# 🌍 Why NDVI?

The **Normalized Difference Vegetation Index (NDVI)** is one of the most widely used remote sensing indices for monitoring vegetation health.

NDVI captures variations in plant chlorophyll content and biomass, making it highly effective for distinguishing crops that exhibit different seasonal growth characteristics.

By analyzing NDVI values over time, machine learning models can identify crop-specific phenological patterns that are difficult to observe from a single satellite image.

---

# 📂 Dataset

The dataset consists of multi-temporal NDVI measurements collected throughout the crop growth season.

### Features

* NDVI01
* NDVI02
* NDVI03
* ...
* NDVI11

Each feature represents vegetation intensity captured during a different stage of crop development.

### Target Classes

* 🌾 Rice
* 🌱 Cotton

---

# 🔍 Exploratory Data Analysis

A comprehensive exploratory analysis was performed to understand both the statistical properties and temporal behavior of the dataset.

The analysis included:

* Statistical summaries
* Missing value inspection
* Duplicate detection
* Outlier analysis
* Feature distributions
* Boxplots
* Histograms
* Correlation heatmaps
* Pairwise feature relationships
* NDVI temporal trend visualization
* Class distribution analysis

These analyses provided valuable insights into crop growth patterns and feature importance before model development.

---

# ⚙️ Data Preprocessing Pipeline

Significant effort was dedicated to preparing the dataset for robust model training.

The preprocessing workflow includes:

* Data cleaning
* Missing value handling
* Duplicate removal
* Feature scaling
* Label encoding
* Train/Test splitting
* Data normalization
* Principal Component Analysis (PCA)

---

# ⚖️ Handling Class Imbalance

Since imbalanced datasets can bias machine learning models, multiple resampling strategies were explored.

Techniques implemented include:

* Random Oversampling
* Random Undersampling
* SMOTE (Synthetic Minority Oversampling Technique)

This enabled fairer learning across crop classes and improved model generalization.

---

# 🤖 Machine Learning Models

Multiple supervised learning algorithms were implemented and compared to identify the best-performing classifier.

### Supervised Models

* XGBoost Classifier
* Random Forest Classifier
* Support Vector Machine (SVM)
* Bagging Classifier

For each model, the workflow included:

* Training
* Hyperparameter tuning
* Cross-validation
* Prediction
* Performance comparison
* Error analysis

---

# 📊 Unsupervised Learning

Beyond supervised classification, clustering techniques were explored to analyze the natural structure of the dataset.

Algorithms investigated include:

* K-Means Clustering
* Hierarchical Clustering
* DBSCAN
* Gaussian Mixture Models (GMM)

These experiments provide additional insight into similarities between vegetation patterns without relying on labeled data.

---

# 📈 Model Evaluation

Models were evaluated using multiple performance metrics to ensure reliable comparison.

### Classification Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC Curve
* ROC-AUC

### Clustering Metrics

* Silhouette Score
* Davies-Bouldin Index
* Calinski-Harabasz Score

Using multiple evaluation metrics provides a more comprehensive assessment than relying solely on accuracy.

---

# 🏗️ Project Workflow

```text
Satellite NDVI Data
          │
          ▼
Data Cleaning
          │
          ▼
Exploratory Data Analysis
          │
          ▼
Feature Engineering
          │
          ▼
Data Balancing
          │
          ▼
Feature Scaling
          │
          ▼
Dimensionality Reduction (PCA)
          │
          ▼
Machine Learning Models
          │
          ▼
Hyperparameter Optimization
          │
          ▼
Performance Evaluation
          │
          ▼
Rice / Cotton Prediction
```

---

# 🛠️ Technologies Used

### Programming Language

* Python

### Data Analysis

* Pandas
* NumPy

### Visualization

* Matplotlib
* Seaborn

### Machine Learning

* Scikit-Learn
* XGBoost

### Scientific Computing

* SciPy

---

# 📁 Repository Structure

```text
NDVI-Rice-and-Cotton-Crop-Classification/
│
├── NDVI Rice and Cotton Crop Classification.ipynb
└── README.md
```

---

# 🌟 Project Highlights

✅ End-to-end machine learning pipeline

✅ Multi-temporal NDVI analysis

✅ Comprehensive exploratory data analysis

✅ Advanced preprocessing and feature engineering

✅ Class imbalance handling using SMOTE and resampling techniques

✅ Multiple supervised learning algorithms

✅ Unsupervised clustering analysis

✅ Hyperparameter optimization

✅ Comparative model evaluation

✅ Remote sensing application for precision agriculture

---

# 🌍 Applications

This project demonstrates techniques applicable to several real-world domains:

* Precision Agriculture
* Smart Farming
* Crop Monitoring
* Yield Prediction
* Land Cover Classification
* Agricultural Decision Support Systems
* Remote Sensing Analytics
* Food Security Planning

---

# 🚀 Future Improvements

Potential extensions include:

* Integration of additional vegetation indices (EVI, SAVI, NDWI)
* Deep learning models such as LSTM for temporal sequence modeling
* Multi-class crop classification
* Satellite image segmentation
* Real-time crop monitoring dashboard
* Cloud-based inference pipeline
* Explainable AI (SHAP/LIME) for feature interpretation

---

# 📚 Skills Demonstrated

This project showcases practical experience in:

* Machine Learning
* Remote Sensing
* Data Preprocessing
* Feature Engineering
* Exploratory Data Analysis
* Supervised Learning
* Unsupervised Learning
* Hyperparameter Optimization
* Model Evaluation
* Scientific Computing
* Data Visualization

---

# 👩‍💻 Author

**Syeda Ayesha Wajahat**

Computer Science Student | AI & Machine Learning Enthusiast

**Areas of Interest**

* Artificial Intelligence
* Machine Learning
* Deep Learning
* Computer Vision
* Natural Language Processing

---

## ⭐ If you found this project useful or interesting, consider giving it a star!

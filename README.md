# Fault Type Prediction using Machine Learning

## Project Overview

This project focuses on identifying the **type of fault** occurring in a system using supervised machine learning techniques. The objective is to classify faults into one of **18 distinct categories**, based on readings or other relevant features.

---

## Current Progress

### Scope Defined
- The initial project scope is limited to **fault type detection** using labeled data.

### Model Selection
- Multiple classification models (SGD, kNN, Decision Tree, Random Forest, Gradient Boosting, Multi-Layer Perceptron) were tested.

### Preliminary Training
- Models were trained and evaluated.
- **Decision Tree** and **Random Forest** had the highest accuracies.

#### Model Performance

| Model                          | Accuracy   |
|-------------------------------|------------|
| SGD Classifier                | 0.3996     |
| k-Nearest Neighbors (kNN)     | 0.5692     |
| Decision Tree                 | 0.7046     |
| Random Forest                 | 0.6914     |
| Gradient Boosting             | 0.6657     |
| Multi-layer Perceptron (MLP)  | 0.5913     |


---

## Next Steps

### Feature Engineering & Scaling
- Apply feature scaling (e.g., StandardScaler, MinMaxScaler) to improve performance.

### Hyperparameter Optimization
- Perform grid search or randomized search to tune hyperparameters of the **Decision Tree** and **Random Forest** to improve performance.

### Model Improvement
- Explore feature selection or dimensionality reduction (PCA, SelectKBest).

### Model Deployment
- Package the final model using **Docker** for easy deployment and reproducibility.
- Develop an API endpoint (e.g., using FastAPI or Flask) for inference.

---

## Future Plans

### Unsupervised Fault Detection
- Introduce **unsupervised learning techniques** (e.g., clustering, autoencoders) for anomaly detection.
- This enables:
  - Pattern discovery without labels
  - **Real-time fault detection and prediction**

---

## Files
- `model_development.ipynb`: Contains data extraction, model training, and evaluation.
- `Inventory of LBNL FDD Data Sets_FCU.pdf`: Contains information on the dataset used.

---



# Titanic Survival Prediction

## Project Overview

This project implements a complete machine learning pipeline for predicting survival outcomes of passengers from the Titanic disaster. The solution includes data exploration, feature engineering, model training, and evaluation.

## 🚀 Motivation

The Titanic dataset is a classic introductory dataset for machine learning, providing valuable insights into data preprocessing, feature engineering, and binary classification problems. 

## 🔧 Technical Aspects

### Data Preprocessing
* Handling missing values (Age, Embarked, Cabin)
* Feature engineering (title extraction, family size)
* Categorical variable encoding
* Normalization and scaling

### Model Training
* Multiple classification algorithms tested:
  * Logistic Regression
  * Decision tree
  * AdaBoost
  * Random Forest
  * Gradient Boosting
  * Support Vector Machines
* Hyperparameter tuning with GridSearchCV
* Cross-validation for robust evaluation

### Evaluation Metrics
* Accuracy score
* Precision and recall
* F1-score
* ROC curves and AUC

## 📦 Installation

### Prerequisites
* Python 3.8+
* Docker (optional)


## How to Run

### Prerequisites
Install the required libraries using pip:
```bash
pip install numpy pandas matplotlib seaborn ipywidgets scikit-learn
```

## Run with Docker

You can run this project in an isolated, reproducible environment using Docker.
A prebuilt image is available on Docker Hub:  
**Image:** [`fatmaalzahra/supervised_classification`](https://hub.docker.com/repository/docker/fatmaalzahra/supervised_classification)



```bash
# 1) Pull the image
docker pull fatmaalzahra/supervised_classification

# 2) Run Jupyter (container exposes port 8888)
docker run --rm -p 8888:8888 fatmaalzahra/supervised_classification

### Execution Steps
1. **Clone the repository** to your local machine
2. **Open the Jupyter notebook**: `Agricultural Crop Recommendation System using Clustering and Classification.ipynb`
3. **Run all cells sequentially** to execute the complete analysis
4. **Follow the step-by-step implementation** provided in the notebook for detailed understanding



## 🛠 Technologies Used

* **Python**: Primary programming language
* **Pandas & NumPy**: Data manipulation and analysis
* **Scikit-learn**: Machine learning algorithms
* **Matplotlib & Seaborn**: Data visualization
* **Jupyter**: Interactive computing environment
* **Docker**: Containerization



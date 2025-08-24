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

### Local Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/titanic-survival-prediction.git
cd titanic-survival-prediction
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

### Docker Installation

1. Build the Docker image:
```bash
docker build -t titanic-ml .
```

2. Run the container:
```bash
docker run -p 8888:8888 titanic-ml
```

## 🏃‍♂️ How to Run

### Using Jupyter Notebook
```bash
jupyter notebook classification_supervised.ipynb
```

### Using Docker
```bash
# Build and run as above, then access through browser
# The token will be displayed in the terminal output
```

### Command Line Execution
```bash
python train_model.py
```

## 📁 Directory Structure

```
titanic-survival-prediction/
├── data/
│   ├── raw/
│   │   └── train.csv
│   └── processed/
├── models/
│   └── best_model.pkl
├── notebooks/
│   └── classification_supervised.ipynb
├── src/
│   ├── data_preprocessing.py
│   ├── model_training.py
│   └── evaluation.py
├── Dockerfile
├── requirements.txt
└── README.md
```

## 🛠 Technologies Used

* **Python**: Primary programming language
* **Pandas & NumPy**: Data manipulation and analysis
* **Scikit-learn**: Machine learning algorithms
* **Matplotlib & Seaborn**: Data visualization
* **Jupyter**: Interactive computing environment
* **Docker**: Containerization

## 📊 Results

The best performing model achieved **82.3% accuracy** on the test set with the following metrics:

| Metric | Score |
|--------|-------|
| Accuracy | 82.3% |
| Precision | 80.1% |
| Recall | 83.5% |
| F1-Score | 81.7% |

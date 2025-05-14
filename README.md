# projects_lab_submissions# 🍷 Red Wine Quality Prediction | EDA & Classification

A machine learning project that aims to predict the quality of red wine based on its physicochemical attributes. This dataset is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality) and is also available on Kaggle.

---

## 📌 Project Overview

This project involves:
- Exploratory Data Analysis (EDA)
- Preprocessing & Imbalance handling
- Building classification models
- Hyperparameter tuning
- Performance evaluation & comparison

Despite the simplicity of the dataset, predicting wine quality is challenging due to **class imbalance** and **subtle differences** between quality scores.

---

## 🧪 Dataset Description

The dataset consists of **1,599 samples** of Portuguese red wine ("Vinho Verde") with **11 physicochemical features** and **1 output variable** (wine quality score from 0 to 10).

### 🔬 Input Features (Physicochemical Tests)
| Feature | Description |
|---------|-------------|
| `fixed acidity`        | Non-volatile acids (e.g., tartaric acid) |
| `volatile acidity`     | Acetic acid content; too much can spoil the wine |
| `citric acid`          | Adds freshness and flavor |
| `residual sugar`       | Sugar remaining after fermentation |
| `chlorides`            | Salt content |
| `free sulfur dioxide`  | SO₂ in free form; protects wine from microbial growth |
| `total sulfur dioxide` | Total SO₂ content |
| `density`              | Related to sugar and alcohol content |
| `pH`                   | Acidity level |
| `sulphates`            | Wine preservative |
| `alcohol`              | Alcohol content in % vol |

### 🏷 Output Variable
- `quality`: Integer score between 0 and 10 (based on sensory data)

---

## 🛠️ Tools & Technologies

- Python 🐍
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Random Forest, Logistic Regression, SVM, XGBoost
- SMOTE (for class imbalance)

---

## 📊 Evaluation Metrics

- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix
- ROC-AUC Curve

---

## 📁 Project Structure

  

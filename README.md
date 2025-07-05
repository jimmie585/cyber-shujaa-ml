#  Wine Classification using Supervised Machine Learning

This project explores and compares six supervised machine learning classification models using the Wine dataset from scikit-learn. The goal is to build, evaluate, and interpret the performance of different models under similar conditions.

---

##  Project Overview

The Wine dataset contains chemical analysis of wines grown in the same region in Italy, derived from three different cultivars. Using this data, we train six classification models and evaluate their performance using accuracy, precision, recall, F1-score, and confusion matrices.

This project demonstrates a complete machine learning workflow from data exploration and preprocessing to model training and evaluation.

---

##  Dataset Description

- **Source**: `sklearn.datasets.load_wine()`
- **Samples**: 178
- **Features**: 13 numeric features (e.g., alcohol, malic acid, color intensity)
- **Classes**: 3 wine categories (`target`: 0, 1, 2)

**Features include:**
- Alcohol  
- Malic acid  
- Ash  
- Alcalinity of ash  
- Magnesium  
- Total phenols  
- Flavanoids  
- Nonflavanoid phenols  
- Proanthocyanins  
- Color intensity  
- Hue  
- OD280/OD315 of diluted wines  
- Proline

---

##  Models Used

The following classification algorithms were implemented using `scikit-learn`:

- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **K-Nearest Neighbors (KNN)**
- **Naive Bayes (GaussianNB)**
- **Support Vector Machine (SVM)**

---

##  Evaluation Metrics

Each model was evaluated on a test set using the following metrics:

- **Accuracy Score**
- **Precision, Recall, F1-Score**
- **Confusion Matrix (visualized using Seaborn heatmap)**

All models were trained and tested using the same standardized and stratified split of the dataset (70% train / 30% test).

---

##  Results Summary

| Model               | Accuracy |
|--------------------|----------|
| Random Forest       | 1.00     |
| Logistic Regression | 0.98     |
| SVM (Linear)        | 0.98     |
| KNN                 | 0.96     |
| Naive Bayes         | 0.96     |
| Decision Tree       | 0.94     |

>  **Best Performing Model:** Random Forest  
> It achieved 100% accuracy and showed consistent precision and recall across all classes.

---

## 🛠 Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/jimmie585/cyber-shujaa-ml.git
cd cyber-shujaa-ml

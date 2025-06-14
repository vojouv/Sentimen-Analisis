# ⚡ Sentiment Analysis on Electric Vehicle Comments using Machine Learning

This project aims to analyze public sentiment toward electric vehicles in Indonesia based on online comments and opinions. A variety of machine learning models are implemented and evaluated to determine the most accurate method for sentiment classification.

---

## 📌 Business Understanding

This phase includes three key activities:

### 1. Define Objectives, Problems, and Needs

- **Objective:**  
  To identify public sentiment based on Indonesian user comments and opinions regarding electric vehicles using various models, including:  
  `RandomForest`, `MultinomialNB`, `GaussianNB`, `SVC`, `XGBoost`, `LogisticRegression`, `DecisionTree`, `Bagging`, `AdaBoost`, and `GradientBoosting`.

- **Problem Statement:**  
  How high is the performance of each model (measured by accuracy, cross-validation mean accuracy, and ROC AUC) when applied to the dataset?

- **Needs:**  
  To understand the sentiment of Indonesian society toward electric vehicles in order to provide insights for stakeholders in making strategic decisions.

---

### 2. Translate Objectives into Project Constraints and Success Parameters

- **Constraint Parameter:**  
  The dataset used is `mobil_listrik.csv`, covering comment data collected from October 2022 to August 2023.

- **Success Parameter:**  
  Successful classification of public sentiment on electric vehicles using evaluation metrics such as `accuracy`, `cv mean accuracy`, and `roc auc`.

---

### 3. Strategy Formulation to Achieve the Goals

- Conduct **data preprocessing** such as `data cleaning` and text normalization.
- Build sentiment analysis models using the defined machine learning algorithms.
- Evaluate model performance using accuracy, cross-validation mean accuracy, and ROC AUC.
- Perform **model validation**.

---

## 📊 Data Understanding

In this case study, the dataset consists of:

- **5 variables**
- **1,517 entries**

### Data Understanding Steps:

1. Identify variables and contents of the dataset  
2. Explore value distributions, null values, and data types  
3. Analyze label balance for classification (imbalanced vs balanced)


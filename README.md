# 🚢 Titanic Survival Analysis

### Exploratory Data Analysis & Machine Learning Classification

An end-to-end Data Science project combining exploratory data analysis (EDA), data preprocessing, visualization, and Gaussian Naive Bayes classification to analyze and predict Titanic passenger survival.

## 📌 Project Overview

This project explores passenger characteristics and survival patterns in the Titanic dataset, then develops a machine learning model to predict whether passengers survived.

## 🎯 Objectives

- Explore and understand the dataset.
- Identify missing values and examine data quality.
- Analyze survival patterns through visualizations.
- Preprocess numerical and categorical features.
- Train a Gaussian Naive Bayes classifier.
- Evaluate performance using classification metrics.

## 🛠️ Technologies & Libraries

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## 📂 Dataset

The dataset contains **891 passenger records and 12 columns**.

The target variable is `Survived`:
- `0` — Did not survive
- `1` — Survived

Selected features include passenger class, sex, age, family relationships, fare, and embarkation port.

## 🔍 Exploratory Data Analysis

The analysis includes:
- Dataset structure and statistical summaries
- Missing-value and duplicate analysis
- Survival distribution
- Survival comparisons by sex and passenger class
- Age and fare distributions
- Embarkation analysis
- Correlation analysis

## ⚙️ Data Preprocessing

- Selected relevant input features and the target variable.
- Excluded passenger identifiers, names, ticket numbers, and cabin information.
- Imputed missing numerical values using the median.
- Imputed missing categorical values using the most frequent category.
- Scaled numerical features.
- Encoded categorical features using one-hot encoding.
- Split the data into training and testing sets using an 80:20 stratified split.
- Integrated preprocessing and classification using a Scikit-learn pipeline.

## 🤖 Machine Learning Model

**Gaussian Naive Bayes**

A probabilistic classification algorithm based on Bayes' theorem, used to predict passenger survival from selected passenger attributes.

## 📊 Model Performance

Evaluation on 179 test samples:

| Metric | Score |
|---|---:|
| Accuracy | 78.77% |
| ROC-AUC | 0.8191 |
| Precision — Did Not Survive | 0.82 |
| Recall — Did Not Survive | 0.85 |
| F1-Score — Did Not Survive | 0.83 |
| Precision — Survived | 0.74 |
| Recall — Survived | 0.70 |
| F1-Score — Survived | 0.72 |

### Confusion Matrix

| Actual / Predicted | Did Not Survive | Survived |
|---|---:|---:|
| Did Not Survive | 93 | 17 |
| Survived | 21 | 48 |

The model correctly classified **141 of 179 passengers**, achieving 78.77% accuracy. The ROC-AUC score of 0.8191 indicates useful discrimination between the two survival classes.

## 📈 Key Learnings

- Exploratory data analysis and data visualization
- Missing-value handling and feature preprocessing
- Numerical and categorical data transformation
- Binary classification using Gaussian Naive Bayes
- Model evaluation using accuracy, precision, recall, F1-score, and ROC-AUC
- Building reproducible machine learning pipelines

## 🔮 Future Improvements

- Compare Naive Bayes with other classification algorithms.
- Apply cross-validation.
- Explore feature engineering.
- Investigate model limitations and classification thresholds.

## 👩‍💻 Author

**Aqsa Batool**  
Computer Science Student | Aspiring Data Scientist

---

*Developed as an educational project to practice exploratory data analysis and machine learning classification.*

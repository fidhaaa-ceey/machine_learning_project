# Machine Learning Models and Predictive Analytics

This repository contains a collection of seven machine learning projects implemented using Python and Scikit-learn. The projects cover regression, classification, regularization, parameter estimation, feature scaling, and text classification.

The experiments use real-world datasets and demonstrate the implementation, training, evaluation, and comparison of different machine learning techniques.

---

## Projects Included

### 1. California Housing Price Prediction

**Objective:**  
Predict median house prices using a single feature from the California Housing dataset.

**Techniques Used:**
- Linear Regression
- Gradient Descent
- Normal Equation
- Feature Scaling

**Evaluation Metrics:**
- Mean Squared Error (MSE)
- R-squared (R²)

**Dataset:** California Housing Dataset

**File:**  
`01-California-Housing-Price-Prediction.ipynb`

---

### 2. Auto MPG Prediction using Polynomial Regression

**Objective:**  
Predict automobile fuel efficiency (MPG) based on engine displacement.

**Techniques Used:**
- Linear Regression
- Polynomial Regression
- Different polynomial degrees

**Evaluation Metrics:**
- Mean Squared Error (MSE)
- R-squared (R²)

**Dataset:** Auto MPG Dataset

**File:**  
`02-AutoMPG-Polynomial-Regression.ipynb`

---

### 3. Diabetes Regression with Ridge and Lasso

**Objective:**  
Compare standard linear regression with regularized regression techniques.

**Techniques Used:**
- Linear Regression
- Ridge Regression
- Lasso Regression
- Cross-validation
- Hyperparameter tuning

**Evaluation Metrics:**
- Mean Squared Error (MSE)
- R-squared (R²)

**Dataset:** Diabetes Dataset

**File:**  
`03-Diabetes-Regression-Regularization.ipynb`

---

### 4. Breast Cancer Classification using MLE and MAP

**Objective:**  
Perform binary classification using logistic regression and compare Maximum Likelihood Estimation with Maximum A Posteriori estimation.

**Techniques Used:**
- Logistic Regression
- Maximum Likelihood Estimation (MLE)
- Maximum A Posteriori (MAP)
- L1 Regularization
- L2 Regularization
- Feature Scaling

**Evaluation Metrics:**
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

**Dataset:** Breast Cancer Wisconsin Dataset

**File:**  
`04-Breast-Cancer-Risk-Classification-MLE-MAP.ipynb`

---

### 5. Multinomial Probability Estimation using MLE and MAP

**Objective:**  
Study parameter estimation for a multinomial distribution using Maximum Likelihood Estimation and Maximum A Posteriori estimation.

**Techniques Used:**
- Multinomial Distribution
- Maximum Likelihood Estimation (MLE)
- Maximum A Posteriori (MAP)
- Dirichlet Prior

**Dataset:** 20 Newsgroups Dataset

**File:**  
`05-Multinomial-Probability-MLE-MAP-Analysis.ipynb`

---

### 6. Diabetes Prediction with and without Feature Scaling

**Objective:**  
Build a logistic regression model to predict diabetes and compare its performance with and without feature scaling.

**Techniques Used:**
- Logistic Regression
- StandardScaler
- Feature Scaling
- Train-Test Split

**Evaluation Metrics:**
- Accuracy
- Precision
- Recall
- F1 Score

**Dataset:** Pima Indians Diabetes Dataset

**File:**  
`06-Diabetes-Risk-Prediction-Feature-Scaling.ipynb`

---

### 7. News Topic Classification using Naive Bayes

**Objective:**  
Classify text documents into different news categories using Naive Bayes algorithms.

**Techniques Used:**
- Text preprocessing
- CountVectorizer
- Multinomial Naive Bayes
- Bernoulli Naive Bayes
- Stop-word removal

**Evaluation Metrics:**
- Accuracy
- Weighted F1 Score

**Dataset:** 20 Newsgroups Dataset

**File:**  
`07-News-Topic-Classification-Naive-Bayes.ipynb`

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Concepts Covered

This project provides practical implementation of the following concepts:

- Linear Regression
- Gradient Descent
- Normal Equation
- Polynomial Regression
- Ridge Regression
- Lasso Regression
- Logistic Regression
- Maximum Likelihood Estimation (MLE)
- Maximum A Posteriori (MAP)
- L1 and L2 Regularization
- Feature Scaling
- Cross-validation
- Hyperparameter Tuning
- Naive Bayes Classification
- Text Classification
- Model Evaluation

---

## Evaluation Metrics

Different projects use different evaluation metrics depending on the type of problem.

### Regression

**Mean Squared Error (MSE)**  
Measures the average squared difference between actual and predicted values.

**R-squared (R²)**  
Measures how well the model explains the variation in the target variable.

### Classification

**Accuracy**  
Percentage of correctly classified samples.

**Precision**  
Measures how many of the samples predicted as positive are actually positive.

**Recall**  
Measures how many of the actual positive samples were correctly identified.

**F1 Score**  
Harmonic mean of precision and recall.

---

## Repository Structure

```text
Machine-Learning-Models-and-Predictive-Analytics/
│
├── README.md
│
├── 01-California-Housing-Price-Prediction.ipynb
├── 02-AutoMPG-Polynomial-Regression.ipynb
├── 03-Diabetes-Regression-Regularization.ipynb
├── 04-Breast-Cancer-Risk-Classification-MLE-MAP.ipynb
├── 05-Multinomial-Probability-MLE-MAP-Analysis.ipynb
├── 06-Diabetes-Risk-Prediction-Feature-Scaling.ipynb
└── 07-News-Topic-Classification-Naive-Bayes.ipynb

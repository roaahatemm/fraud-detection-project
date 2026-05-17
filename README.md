# Financial Fraud Detection using Machine Learning

## Project Overview
This project focuses on detecting fraudulent financial transactions using machine learning techniques.  
The dataset is highly imbalanced, making fraud detection a challenging classification problem.

The project includes:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Handling Imbalanced Data using SMOTE
- Logistic Regression Baseline Model
- Random Forest Classification
- Hyperparameter Tuning using GridSearchCV
- Model Evaluation and Comparison

---

## Dataset
The dataset contains financial transaction information such as:
- Transaction amount
- Merchant details
- Customer information
- Transaction location
- Fraud labels

Target Variable:
- `is_fraud`
    - 0 → Legitimate Transaction
    - 1 → Fraudulent Transaction

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn

---

## Machine Learning Workflow

### 1. Data Preprocessing
- Removed unnecessary columns
- Encoded categorical variables
- Performed train-test split

### 2. Handling Imbalanced Data
SMOTE (Synthetic Minority Oversampling Technique) was applied only on the training dataset to balance fraud and non-fraud classes.

### 3. Models Used
- Logistic Regression
- Random Forest Classifier
- Tuned Random Forest using GridSearchCV

---

## Model Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Best Model Performance
The Random Forest Classifier achieved the best overall performance for fraud detection compared to Logistic Regression and the Tuned Random Forest model.

It provided a strong balance between:
- Precision
- Recall
- F1-Score

making it the most effective model for detecting fraudulent transactions in this project.

---

## Author
Roaa
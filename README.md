# Credit Quality Prediction using Machine Learning

## Project Overview
This project assesses the credit quality of bank customers using machine learning. The goal is to classify customers as "Good" or "Bad" based on various attributes.

## Dataset Description

This project uses a **credit dataset** to assess the creditworthiness of bank customers. The dataset contains **1000 rows** and **62 features**, capturing a wide range of customer attributes.  

### Target Variable
- **Class**: Binary target indicating credit quality  
  - `Good` – low credit risk  
  - `Bad` – high credit risk  

### Feature Categories
1. **Numeric Features**
   - `Duration`, `Amount`, `InstallmentRatePercentage`, `ResidenceDuration`, `Age`, `NumberExistingCredits`, `NumberPeopleMaintenance`  

2. **Binary/Categorical Features**
   - **Demographics:** `Telephone`, `ForeignWorker`, `Personal.*` (marital status, gender)  
   - **Financial Status:** `CheckingAccountStatus.*`, `SavingsAccountBonds.*`, `OtherDebtorsGuarantors.*`  
   - **Credit History:** `CreditHistory.*`  
   - **Purpose of Credit:** `Purpose.*` (e.g., NewCar, Furniture, Education, Business)  
   - **Employment & Job:** `EmploymentDuration.*`, `Job.*`  
   - **Property & Housing:** `Property.*`, `Housing.*`  
   - **Installment Plans:** `OtherInstallmentPlans.*`  

### Key Points
- **Mix of numeric and categorical features**, making this dataset ideal for **classification modeling**.  
- Provides opportunities to explore **feature engineering, handling imbalanced classes, and comparing multiple machine learning models** (logistic regression, tree-based models, KNN, SVM).  
- The dataset is **not included** due to academic/privacy reasons; the code is compatible with this structure.



## Methods
- **Logistic Regression**: Fitted with different probability thresholds (20%, 35%, 50%) to evaluate performance using confusion matrices.
- **Tree-based Models**: Classification trees, bagging, and random forests, compared against logistic regression using AUC and ROC curves.
- **Other Models**: k-Nearest Neighbors (KNN) and Support Vector Machines (SVMs) were also explored.
- **Class Imbalance Handling**: Techniques applied to improve model fairness.

## Evaluation
The dataset is split into training and test sets for generalization assessment. Emphasis is placed on **accuracy, interpretability, and fairness** in predicting customer credit quality.

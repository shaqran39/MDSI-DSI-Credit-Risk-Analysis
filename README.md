# MDSI-DSI-Credit-Risk-Analysis


This repository contains the implementation and analysis of a credit risk assessment project conducted by Group Orion for the 36100 Data Science for Innovation course at the University of Technology Sydney.

## Team Members
- **Shaqran Bin Saleh** (Student ID: 25010238)
- **Hasnaine Ahmed Dihan** (Student ID: 25382363)
- **Al Jobyer Swajoy** (Student ID: 25389483)
- **Masuma Tasnim Jerin** (Student ID: 25097799)
- **Md Eusuf Ali Rinku** (Student ID: 25215411)

## Table of Contents
1. [Introduction](#introduction)
2. [Literature Review](#literature-review)
3. [Setup](#setup)
4. [Approach](#approach)
5. [Results](#results)
6. [Conclusion](#conclusion)
7. [References](#references)

## Introduction
This project aims to assess the credit risk of borrowers using various machine learning models. The primary focus is on understanding how different borrower characteristics impact loan defaults. We used logistic regression and decision tree classifiers for predicting loan defaults and evaluated their performance.

## Literature Review
The literature review covers the significance of credit risk management in banking, highlighting how poor practices and institutional constraints contribute to credit risk. Key studies and findings from different countries are discussed, showing both positive and negative relationships between credit risk and bank performance.

## Setup
The setup section includes data preparation steps, such as handling missing values, encoding categorical variables, and normalizing numerical features. We provide visual insights through correlation matrices and various plots to illustrate relationships between borrower characteristics and loan statuses.

## Approach
### Proposed Model and Benchmark Models
We used two machine learning models:
- **Logistic Regression:** Chosen for its interpretability and effectiveness in binary classification.
- **Decision Tree Classifier:** Selected for its ability to handle non-linear relationships and complex interactions between features.

### Method of Analysis
1. **Data Preparation:** Includes pre-processing steps for dealing with missing values, encoding, and normalization.
2. **Feature Engineering:** Based on insights from the correlation matrix.
3. **Correlation Analysis:** Identifies significant variables for predicting defaults.
4. **Hypothesis Testing:** Uses Chi-Squared and Kruskal-Wallis tests to confirm relationships between features and loan defaults.
5. **Predictive Modeling:** Deploys logistic regression and decision tree classifiers, with performance evaluated using precision, recall, F1-score, and accuracy.
6. **Model Evaluation and Selection:** Assesses models based on their predictive power and interpretability.

## Results
The logistic regression model performed well in identifying non-defaulters but struggled with defaulters. The decision tree classifier, after fine-tuning, provided a more balanced performance across both categories. Detailed performance metrics and visual evaluations are provided.

### Limitations
- **Data Imbalance:** Uneven distribution of classes impacted model performance.
- **Model Constraints:** Logistic regression's inability to capture complex relationships and decision trees' susceptibility to overfitting.
- **Error Patterns:** Issues with false negatives in both models.

### Possible Improvements
- Balancing the dataset using techniques like SMOTE.
- Creating new features from existing data.
- Employing ensemble methods for stronger predictive power.

## Conclusion
Our study identified key predictors of loan defaults and demonstrated the effectiveness of logistic regression and decision tree models in credit risk assessment. Future work will focus on addressing limitations and exploring advanced techniques to improve predictive accuracy.

## References
- Boahene SH, D. J. (2012). Credit risk and profitability of selected banks in Ghana. *Research Journal of Finance and Accounting*.
- Kithinji, A. M. (2010). Credit risk management and profitability of commercial banks in Kenya.
- Kolapo, T. F. (2012). Credit risk and commercial banks’ performance in Nigeria: A Panel Model. *Australian Journal of Business and Management Research*, 31-38.
- Million Gizaw, M. K. (2015). The impact of credit risk on profitability performance of commercial banks in Ethiopia. *African Journal of Business Management*, 59-66.
- Poudel, R. P. (2012). The impact of credit risk management on financial performance of commercial banks in Nepal. *International Journal of Arts and Commerce*.

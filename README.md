# Bank Marketing Prediction — Theoretical Machine Learning

**MSc Data Science — Thompson Rivers University, BC, Canada (2024)**

---

## Overview

This project applies multiple machine learning classification algorithms to predict whether a bank client will subscribe to a term deposit, based on a real-world Portuguese bank marketing dataset with 45,211 instances and 16 features, including demographics, financial status, and campaign data.

The goal was to compare model performance across Logistic Regression, KNN, and Random Forest using cross-validation and bootstrapping, and identify the best approach for binary classification in a banking context.

---

## Key Results

| Model | Accuracy | Specificity | PPV |
|---|---|---|---|
| Logistic Regression | 90.60% | 98.25% | 70.21% |
| KNN (k=5) | 87.72% | 97.62% | 38.71% |
| Random Forest | **90.93%** | 97.50% | 67.74% |

**Best model: Random Forest with 90.93% accuracy**

---

## Dataset

- **Source:** UCI Machine Learning Repository — Bank Marketing Dataset
- - **Instances:** 45,211 (full dataset) / 4,521 (sample)
- - **Features:** 16 input variables + 1 output variable
- - **Target:** Will the client subscribe to a term deposit? (yes/no)
- - **Domain:** Portuguese banking institution direct marketing campaigns (2008–2010)
       
- ---

## Methodology

1. **Exploratory Data Analysis (EDA)** — Summary statistics, histograms, correlation analysis, missing value checks
2. 2. **Data Preprocessing** — Feature encoding, train/test split
3. 3. **Model Training** — 5-fold cross-validation for all three models
4. 4. **Model Evaluation** — Confusion matrix, accuracy, sensitivity, specificity, PPV
5. 5. **Validation** — 1000-iteration bootstrapping to verify model authenticity
                   
6. ---
                   
7. ## Tools & Technologies
                   
8. - **Language:** R
- - **Libraries:** caret, ggplot2, MASS, glmnet, neuralnet, corrplot, boot, car, tidyr, reshape2
- - **Techniques:** Logistic Regression, KNN, Random Forest, Cross-Validation, Bootstrapping, EDA
                          
- ---

 ## Academic Context

- **Institution:** Thompson Rivers University, Kamloops, BC, Canada
- **Degree:** Master of Science in Data Science
- **Course:** Theoretical Machine Learning
- **Date:** April 2024
                                
- ---

## Authors

**Sagar & Michael Ahana**
- LinkedIn: [linkedin.com/in/sagar96](https://www.linkedin.com/in/sagar96/)
- GitHub: [github.com/sagarkhatri96](https://github.com/sagarkhatri96)

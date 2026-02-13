# Social Media Addiction Classification

## Project Overview

This is an end-to-end Data Science project focused on predicting social media addiction using behavioral and psychological indicators.

The objective is to classify individuals as addicted or non-addicted based on usage patterns, mental health metrics, and lifestyle features.

This problem is formulated as a **binary classification task**.

---

## Problem Statement

With increasing digital engagement, identifying individuals at risk of social media addiction is crucial for mental well-being and academic performance.

This project aims to:
- Analyze behavioral and psychological factors
- Build classification models
- Identify key predictors of addiction
- Evaluate model robustness and reliability

---

## Methodology

1. Data Cleaning and Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Encoding (Categorical Variables)  
4. Train-Test Split  
5. Feature Scaling (for Logistic Regression)  
6. Model Training:
   - Logistic Regression
   - Random Forest Classifier
7. Model Evaluation using:
   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - Confusion Matrix
8. Correlation Analysis
9. Robustness Check by Removing Highly Correlated Features  

---

## Models Used

### Logistic Regression
- Baseline linear classification model
- Interpretable and efficient

### Random Forest Classifier
- Captures non-linear relationships
- Handles feature interactions effectively
- Demonstrated strong predictive performance

---

## Evaluation Metrics

- **Accuracy** – Overall correctness of predictions  
- **Precision** – Correct positive predictions ratio  
- **Recall** – Ability to identify addicted individuals  
- **F1 Score** – Balance between precision and recall  
- **Confusion Matrix** – Detailed classification performance  

The model achieved approximately **99% accuracy**, with strong balance between precision and recall.

---

## Key Insights

- Behavioral indicators such as daily usage hours, conflicts over social media, and mental health scores strongly correlate with addiction.
- Multiple features contribute significantly to prediction.
- Removing a highly correlated feature did not significantly reduce performance, confirming model robustness.

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Limitations

- Dataset may contain self-reported bias.
- Strong feature correlations may simplify classification.
- Real-world data may contain more noise.
- External environmental and psychological factors were not included.
- Model performance should be validated on independent datasets.

---

## Future Improvements

- Perform hyperparameter tuning for optimization
- Add ROC-AUC analysis
- Validate using cross-validation
- Explore advanced models such as XGBoost
- Deploy model as a web-based risk assessment tool

---

## Conclusion

This project demonstrates how supervised machine learning can effectively classify social media addiction using behavioral indicators. The model shows strong predictive performance while maintaining interpretability and robustness through correlation analysis and validation checks.

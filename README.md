# Predictive Analytics for Customer Churn in Financial Services

## Project Overview

This capstone project focuses on predicting customer churn for a financial institution using machine learning and statistical analysis. The primary goal was to identify high-risk customers before they leave, allowing for proactive intervention and resource optimization. The project achieved approximately 86% ROC-AUC using interpretable AI models.

## Key Features

- **Targeted Prediction**: Identification of the top drivers of churn, specifically number of products, age, and geography.
- **Advanced Modeling**: Implementation of five different algorithms, with ensemble models like Random Forest and Gradient Boosting providing the best performance.
- **Ethical AI**: Incorporation of fairness, transparency, privacy, and accountability principles.
- **Interpretability**: Use of SHAP and LIME to provide model-agnostic explanations for individual predictions.

## Dataset

- **Source**: Bank Churn Modelling dataset from the YBI Foundation repository.
- **Size**: 10,000 anonymized customer records.
- **Variables**: 14 columns covering demographics (geography, age, gender), banking relationships (tenure, product count, active status), and financial indicators (credit score, balance, salary).

## Methodology (CRISP-DM)
The project followed the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework over a 12-week period:

- **Business Understanding**: Defined churn objectives and established a success metric of >75% ROC-AUC.
- **Data Understanding**: Conducted EDA and statistical hypothesis testing (Chi-Square, Mann-Whitney U).
- **Data Preparation**: Handled class imbalance using SMOTE and performed feature engineering (e.g., BalanceToSalary_Ratio, Age_Group).
- **Modeling**: Trained five algorithms with hyperparameter tuning via GridSearchCV and 5-fold cross-validation.
- **Evaluation**: Compared models using multiple metrics and conducted bias detection/fairness analysis.

## Results

- **Top Model**: Tuned Random Forest and Gradient Boosting achieved the highest ROC-AUC (~0.86).
- **Key Churn Drivers**:

  - Number of Products: The strongest driver of churn.
  - Age: Older customers showed a higher propensity to churn.
  - Geography: Customers in Germany had significantly higher churn rates compared to France and Spain.
  - Success Metrics: Exceeded the initial success threshold of 75% ROC-AUC.
 
## Tools & Technologies
- **Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn 
- **Interpretability**: SHAP, LIME 
- **Imbalance Handling**: SMOTE

## Additional Resources
- [Notebook](https://github.com/thant-thiha/predictive-analytics-customer-churn-financial-services/blob/main/Financial_Services_Churn_Predictive_Analytics_Notebook.ipynb)
- [Poster Presentation](https://github.com/thant-thiha/predictive-analytics-customer-churn-financial-services/blob/main/Financial_Services_Churn_Predictive_Analytics_Poster_Presentation.pdf)
- [Report](https://github.com/thant-thiha/predictive-analytics-customer-churn-financial-services/blob/main/Financial_Services_Churn_Predictive_Analytics_Report.docx)

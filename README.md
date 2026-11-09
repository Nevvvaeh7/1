# Home Loan Default Prediction

Predicting home equity loan defaults to identify key underwriting risk drivers.

## Key Results
- Recall 80%+ and accuracy 85%+ in detecting defaults
- DTI ratio and 12-month delinquency are the strongest risk drivers

## Data
HMEQ dataset (10K+ home equity loan records) – [source link]

## Approach
1. EDA and data cleaning (missing values, outliers)
2. Feature engineering
3. Models: Logistic Regression, Decision Tree, Random Forest, XGBoost
4. Evaluation: recall, precision, ROC-AUC (recall prioritized to catch defaults)

## Business Takeaways
[2-3 sentences: what a credit risk team would do with these findings]

## Tech Stack
Python · pandas · scikit-learn · XGBoost · matplotlib

## How to Run
pip install -r requirements.txt, then open notebooks/default_prediction.ipynb# 1

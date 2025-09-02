# Credit Risk Prediction Model

This project is part of my **first internship project with CodeAlpha**.  
It focuses on predicting **loan default risk** using a real-world credit risk dataset.

## Dataset
- Over **32,000 loan records**  
- Features: age, income, employment length, home ownership, loan intent, interest rate, credit history  
- Target: loan status (default or non-default)

## Workflow
- Cleaned the dataset and removed unrealistic values  
- Handled missing values with median imputation  
- One-hot encoded categorical variables  
- Balanced the dataset using **SMOTE**  
- Scaled numerical features  
- Trained and validated a **LightGBM model** with cross-validation

## Results
- **Accuracy**: 93%  
- Balanced **precision** and **recall**, showing reliable performance across both classes  
- Top predictive features: loan intent, income, interest rate, employment length

## Why 93% Accuracy
**Positive**  
- The model captured strong, meaningful patterns  
- Proper preprocessing and balancing improved performance  
- LightGBM handled numeric and categorical data effectively  

**Limitations**  
- Dataset lacks some important borrower details such as spending patterns or long credit history  
- Credit risk is complex, and some real-world factors are missing  
- Minority class prediction remains harder despite balancing

## Notebook
[CodeAlpha_CreditScoringModel.ipynb](https://github.com/KareemEzzaldin/CodeAlpha-Credit-Scoring-Model/blob/main/CodeAlpha_CreditScoringModel.ipynb)

# Credit Risk Prediction Project

## About the Project
This project is about predicting whether a credit card customer is likely to default in the next month.  
I built this project to practice applying machine learning to a real-world problem and to understand how business decisions affect model evaluation.

---

## Problem Statement
In credit-related problems, missing a defaulter can be costly for banks and financial institutions.  
Because of this, focused more on **recall** rather than accuracy, so that fewer defaulters are missed by the model.

---

## Dataset
The dataset contains information about customers’ credit limits, bill amounts, payment history, and repayment behavior.  
The target variable shows whether a customer defaulted or not.  
The data is imbalanced, with fewer default cases compared to non-default cases.
The dataset is publicly available on Kaggle and is not included in this repository.

---

## What I Did
- Cleaned the dataset and removed unnecessary columns
- Checked class imbalance in the target variable
- Used **Logistic Regression** as a baseline model to understand the data
- Used **Random Forest** to capture non-linear patterns in the data
- Handled class imbalance using class weights
- Tuned the probability threshold to reduce missed defaulters
- Evaluated the models using confusion matrix, recall, and ROC-AUC

---

## Model Evaluation
Instead of only using accuracy, I used:
- Confusion Matrix
- Recall and F1-score
- ROC-AUC score

Threshold tuning helped improve recall by adjusting how strict the model is while predicting defaulters.

---

## Key Learnings
- Accuracy alone is not reliable for imbalanced datasets
- Logistic Regression is useful as a simple and interpretable baseline
- Random Forest performed better in identifying defaulters
- Changing the decision threshold can significantly affect model performance
- Confusion matrix is very useful for understanding model mistakes

---

## Limitations
- The model is trained on historical data only
- Real-world deployment would need regular monitoring and updates
- Feature importance does not mean causation

---

## Future Improvements
- Try cost-based evaluation metrics
- Experiment with probability calibration
- Explore other ensemble models

---

## Tools Used
- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn




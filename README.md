# Credit-Card-Fraud-Detection
Detects fraudulent credit card transactions using classification algorithm.

##  Abstract  
With the rapid growth of e-commerce and digital transactions, credit card fraud has become a major issue in modern banking systems.  
This project aims to detect fraudulent transactions using Machine Learning, specifically the Random Forest algorithm, which provides higher accuracy and robustness compared to other models.

## Introduction  
Online transactions such as Google Pay, PayPal, and banking apps are highly convenient — but they also increase the risk of fraud.  
This project builds a fraud detection system using Random Forest, which can analyze large transaction datasets and distinguish between legitimate and fraudulent transactions.

# Objectives  
- Identify fraudulent transactions accurately  
- Reduce financial losses for banks and customers  
- Minimize false positives (legitimate transactions wrongly flagged)  
- Improve model efficiency through data preprocessing & feature engineering  
- Maintain customer trust and secure financial systems  

## Methodology  
The workflow of this project includes:
1.Data Collection→ Kaggle dataset  
2.Data Preprocessing → Handling missing values, scaling, and encoding  
3.Resampling→ Balancing data using under-sampling and over-sampling  
4.Model Training→ Training Random Forest classifier  
5.Evaluation → Using Accuracy, Precision, Recall, F1-score, ROC-AUC  
6.Model Deployment (Future Scope) → Deploying in real-time fraud detection systems  

### Steps:
1. Split dataset into **train (70%)** and **test (30%)**
2. Train Random Forest Classifier
3. Evaluate using metrics below

## Results
Logistic Regression
Accuracy-98.3% 
Precison-96.8% 
Reall-97.1%
F1-score-96.9% 
The Random Forest model achieved the best balance between accuracy and recall, making it ideal for fraud detection tasks.


## References
- [ResearchGate Paper – Credit Card Fraud Detection Techniques](https://www.researchgate.net/publication/319612975_A_Survey_of_Credit_Card_Fraud_Detection_Techniques)  
- [Kaggle Notebook – Random Forest Fraud Detection](https://www.kaggle.com/code/hassanamin/credit-card-fraud-detection-using-random-forest)

 “Enhancing security through intelligent fraud detection.”


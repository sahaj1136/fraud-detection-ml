# Credit Card Fraud Detection 

This project applies machine learning techniques to detect fraudulent credit card transactions. It uses a real-world dataset and includes preprocessing, feature engineering, model building, and evaluation.

## Dataset
- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/kartik2112/fraud-detection)
- Contains transactions labeled as **fraud** or **non-fraud**.

## Models Used
- Logistic Regression
- Random Forest Classifier

## Techniques Applied
- Data cleaning & preprocessing
- SMOTE (Synthetic Minority Over-sampling Technique) for handling class imbalance
- Feature scaling
- Model evaluation with confusion matrix, ROC-AUC, precision-recall, and F1-score

## Metrics Used
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

## Highlights
- AUC ~ 0.97 with Random Forest
- Effective handling of class imbalance using SMOTE
- Visualizations for fraud patterns by category, hour, and transaction type

## Libraries
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- imbalanced-learn

## Usage
1. Install required packages:  
   `pip install -r requirements.txt`
2. Run the notebook `CreditCardFraudDetection.ipynb` step-by-step.
3. Ensure you have Kaggle API access set up if using `kagglehub`, or manually place `fraudTrain.csv` in the working directory.
4. ## Dataset
   Available on Kaggle:  
   [https://www.kaggle.com/datasets/kartik2112/fraud-detection](https://www.kaggle.com/datasets/kartik2112/fraud-detection)

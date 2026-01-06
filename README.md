# Credit Card Fraud Detection Using Machine Learning

## Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset is analyzed, preprocessed, and used to train classification models that can identify whether a transaction is fraudulent or legitimate.

---

## Objective
- Analyze credit card transaction data  
- Perform data preprocessing and handle class imbalance  
- Implement machine learning models for fraud detection  
- Compare model performance  

---

## Models Used
The following machine learning models are used in this project:
- **Random Forest (RF)**
- **XGBoost (Extreme Gradient Boosting)**

These models are effective for classification tasks and handle complex patterns in large datasets.

---

## Tools and Technologies
- Python  
- Jupyter Notebook  
- NumPy  
- Pandas  
- Scikit-learn  
- XGBoost  
- Matplotlib / Seaborn  

---

## Methodology
1. **Data Loading**  
   The dataset is loaded and explored to understand its structure.

2. **Data Preprocessing**  
   Data cleaning, feature scaling, and handling of class imbalance are performed.

3. **Model Training**  
   Random Forest and XGBoost models are trained using the processed dataset.

4. **Model Evaluation**  
   Performance is evaluated using accuracy, precision, recall, F1-score, and confusion matrix.

5. **Model Comparison**  
   Both models are compared to determine the better-performing model.

---

## Results
- Both models show good performance in fraud detection  
- XGBoost performs better on imbalanced data  
- Random Forest provides stable baseline results  

Detailed results are available in the notebook.

---

## Project Structure
├── README.md
├── best_fraud_model.pkl
├── credit_card_fraud_detection.ipynb
├── creditcard.csv

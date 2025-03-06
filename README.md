# Credit Card Fraud Detection  

A machine learning project for detecting fraudulent credit card transactions using multiple classification models.  

## 📌 Overview  
This project analyzes transaction data from `creditcard.csv` to classify transactions as **fraudulent (1)** or **legitimate (0)**.  
It addresses **class imbalance** and evaluates different machine learning models for fraud detection.  

## Features  
- **Data Preprocessing**: Handling missing values and balancing the dataset.  
- **Exploratory Data Analysis**: Understanding fraud vs. non-fraud transactions.  
- **Model Training**: Applying **Logistic Regression, Decision Trees, Naive Bayes Classifier and Gradient Boosted Tree.**  
- **Evaluation**: Comparing model performance and accuracy.  

## Dataset  
The dataset contains anonymized transaction features and a **Class** column:  
- `0` → Legitimate Transaction  
- `1` → Fraudulent Transaction  

##  Installation & Usage  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/Credit-Card-Fraud-Detection.git
   cd Credit-Card-Fraud-Detection
2. Install dependencies: pip install -r requirements.txt
3. Run: jupyter notebook
4. Open: Credit_card_fraud.ipynb

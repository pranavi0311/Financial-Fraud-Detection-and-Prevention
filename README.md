# Risk Score-based Financial Fraud Detection and Prevention

A machine learning-based system to detect and flag suspicious financial transactions, helping prioritize high-risk cases for review.

# Overview
This project uses Python and machine learning models to analyze transaction data and identify potentially fraudulent activity. Each transaction is assigned a risk score, allowing suspicious transactions to be prioritized based on risk level for faster, more efficient decision-making.

## Tech Stack
- Python
- Scikit-learn 
- Pandas, NumPy
- SMOTE (for handling class imbalance)

## Key Features
- Risk scoring for each transaction
- Class imbalance handling using SMOTE to improve detection of rare fraud cases
- Pattern analysis to reduce false positives
- Prioritized output for efficient review of high-risk transactions

## How It Works
1. Load and preprocess transaction data
2. Apply SMOTE to balance the fraud vs. non-fraud classes
3. Train a classification model ( Logistic Regression / Random Forest )
4. Generate a risk score for each transaction
5. Output ranked/flagged transactions for review

## How to Run
```bash
pip install -r requirements.txt
python main.py
```

## Results
<img width="1920" height="1080" alt="Screenshot (32)" src="https://github.com/user-attachments/assets/d647214a-a536-466b-9a58-dce35f3d1919" />
<img width="1920" height="1080" alt="Screenshot (36)" src="https://github.com/user-attachments/assets/65878139-febf-4a0c-a436-bd73bcf15751" />
<img width="1920" height="1080" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/8a3d7e4d-bbf9-45b2-aa9b-6ca01fb269b6" />
<img width="1920" height="1080" alt="Screenshot (33)" src="https://github.com/user-attachments/assets/83136536-1626-4199-a374-f2dd3bc71969" />


## Future Improvements
- Real-time transaction scoring
- Model explainability for flagged transactions

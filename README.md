Credit Card Fraud Detection 💳🔍
This project aims to build a machine learning model for detecting fraudulent credit card transactions. It is designed to help identify and flag risky activity in financial data, with a user-friendly workflow and reproducible code.

📁 Dataset
The dataset records transactions by European cardholders in September 2013.

Highly unbalanced: Frauds make up a tiny proportion of all transactions.

Features:

Time: Seconds elapsed between each transaction and the first in the dataset.

Amount: Transaction amount.

V1–V28: Anonymized principal components (PCA-transformed).

Class: Target label (1 = fraud, 0 = normal).

🤖 Model
Logistic Regression classifies transactions as fraudulent or normal.

Handling imbalance:
Majority class (normal transactions) is under-sampled for balanced training.

Evaluation:

Accuracy (Train): 94.16%

Accuracy (Test): 93.91%


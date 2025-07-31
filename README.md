# 💳 Credit Card Fraud Detection

## 🔍 Project Overview  
This project builds a machine learning model to detect fraudulent credit card transactions. It aims to flag risky patterns in financial data using a clean, reproducible workflow.

---

## 📁 Dataset Details  
- **Source**: European cardholder transactions, September 2013  
- **Imbalance**: Fraudulent cases form a tiny fraction of the data  
- **Features**:  
  - `Time`: Seconds since the first transaction  
  - `Amount`: Transaction value  
  - `V1–V28`: PCA-transformed features for anonymization  
  - `Class`: Target label (`1` = Fraud, `0` = Normal)

---

## 🤖 Modeling Approach  
- **Model**: Logistic Regression  
- **Imbalance Strategy**: Undersampling the majority class (normal) to create a balanced training set  
- **Performance Metrics**:  
  - ✅ **Train Accuracy**: 94.16%  
  - ✅ **Test Accuracy**: 93.91%

---

> ⚙️ Ready to use on Colab with no setup — ideal for rapid prototyping and evaluation.


# 💳 Online Transaction Fraud Detection System

## 📌 Overview
This project focuses on detecting **fraudulent online financial transactions** using **Machine Learning classification techniques**.  
The goal is to accurately identify suspicious transactions while minimizing false positives, ensuring safer digital payments.

This project is designed as a **real-world, industry-oriented ML use case** and is suitable for academic projects, portfolios, and interviews.

---

## 🧠 Problem Statement
With the rapid growth of **online banking and digital payments**, fraudulent transactions have increased significantly.  
Manual detection is inefficient, error-prone, and slow.

👉 **Machine Learning helps automate fraud detection** by learning transaction patterns and identifying anomalies in real time.

---

## 📊 Dataset Information
- 📁 **Dataset:** Online Transaction Dataset  
- 🌐 **Source:** Kaggle / Synthetic Financial Dataset  
- 🧾 **Records:** Large-scale transactional data  
- 🎯 **Target Variable:** `isFraud` (0 = Genuine, 1 = Fraud)

### 🔑 Key Features
- `type` – Transaction type (PAYMENT, TRANSFER, CASH_OUT, etc.)
- `amount` – Transaction amount
- `oldbalanceOrg` – Sender balance before transaction
- `newbalanceOrig` – Sender balance after transaction
- `oldbalanceDest` – Receiver balance before transaction
- `newbalanceDest` – Receiver balance after transaction

---

## 🤖 Machine Learning Approach
### 🔹 Classification Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- (Optional) XGBoost / Gradient Boosting

### 🧪 Techniques Applied
- Feature Engineering
- Handling class imbalance
- Train-test split
- Model evaluation & comparison

---

## 🛠 Tech Stack
- 🐍 Python  
- 📊 NumPy  
- 🗂 Pandas  
- 📈 Matplotlib  
- 🎨 Seaborn  
- 🤖 Scikit-learn  

---

## ⚙️ Project Workflow
1. 📥 Import required libraries  
2. 📂 Load and inspect the dataset  
3. 🧹 Data cleaning & preprocessing  
4. 🔍 Exploratory Data Analysis (EDA)  
5. 🧠 Train classification models  
6. 📊 Evaluate using performance metrics  
7. 🚨 Detect fraudulent transactions  

---

## 📈 Model Evaluation Metrics
- ✅ Accuracy  
- 🎯 Precision  
- 🔁 Recall  
- 📉 F1-Score  
- 🧮 Confusion Matrix

## 🚀 Future Enhancements

-🧠 Drift-aware fraud detection

-⚡ Real-time streaming detection

-🌐 Deploy using Streamlit / Flask

-📊 Add SHAP for explainable AI

These metrics ensure the model balances **fraud detection accuracy** and **false alarm reduction**.

---

## 📊 Results & Insights
- ✔ Successfully detects fraudulent transactions
- ✔ Handles highly imbalanced data effectively
- ✔ Random Forest performs better for complex patterns
- ✔ Feature importance highlights risky transaction behaviors

## 👤 Author

**Nandan**  
📌 AI & Machine Learning Enthusiast  

🔗 **GitHub:** https://github.com/Nandan0402  
🔗 **LinkedIn:** https://www.linkedin.com/in/nandan0402


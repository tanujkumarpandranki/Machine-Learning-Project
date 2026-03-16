# 💳 Credit Card Fraud Detection using XGBoost

This project detects fraudulent credit card transactions using **Machine Learning**.  
The model uses **XGBoost Classifier** to identify whether a transaction is **Fraudulent or Legitimate** based on transaction features.

---

## 📌 Project Overview

Credit card fraud is a serious financial problem worldwide. Machine Learning models can analyze transaction patterns and identify suspicious activities.

In this project, a **machine learning classification model** is built using **XGBoost** to detect fraudulent transactions from credit card transaction data.

---

## ⚠️ Imbalanced Dataset

The credit card transaction dataset is **highly imbalanced**.

- **Class 0 → Normal Transactions**
- **Class 1 → Fraud Transactions**

Fraud transactions represent only a **very small percentage of the dataset**, which makes fraud detection challenging.

Because of this imbalance, model performance is evaluated using a **Confusion Matrix** instead of relying only on accuracy.

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib / Seaborn  

---

## ⚙️ Project Workflow

### 1️⃣ Data Loading
- Load the credit card transaction dataset

### 2️⃣ Data Preprocessing
- Check for missing values
- Prepare data for model training

### 3️⃣ Exploratory Data Analysis (EDA)
- Analyze fraud vs non-fraud transactions
- Visualize class distribution

### 4️⃣ Model Training
- Split dataset into **training and testing data**
- Train the model using **XGBoost Classifier**

### 5️⃣ Model Evaluation
- Predict fraud transactions
- Evaluate performance using:
  - **Confusion Matrix**
  - **Accuracy Score**

---

## 📊 Model Evaluation

The **Confusion Matrix** is used to analyze the model performance:

- **True Positives (TP)** → Correctly predicted fraud transactions  
- **True Negatives (TN)** → Correctly predicted normal transactions  
- **False Positives (FP)** → Normal transactions predicted as fraud  
- **False Negatives (FN)** → Fraud transactions predicted as normal  

This helps better understand the effectiveness of fraud detection.

---

## 📂 Project Structure

```
credit-card-fraud-detection
│
├── fraud_detection.ipynb
├── dataset.csv
├── README.md
```

---

## 🚀 Future Improvements

- Apply **SMOTE for handling class imbalance**
- Try **Deep Learning models**
- Deploy the model using **Streamlit or Flask**

---

## 👨‍💻 Author

**Tanuj Kumar**  
B.Tech CSE (AI & ML)

GitHub: https://github.com/yourusername

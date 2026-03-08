# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

Credit card fraud is one of the major challenges faced by financial institutions today. Fraudulent transactions lead to significant financial losses every year.

This project aims to build a **machine learning model that can identify fraudulent credit card transactions** based on transaction features.

Using a **Kaggle credit card fraud dataset**, we analyze the transaction data and train models to distinguish between **legitimate and fraudulent transactions**.

---

## 📂 Dataset

The dataset used in this project is the **Credit Card Fraud Detection Dataset from Kaggle**.

Dataset link:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

### Dataset Features

* The dataset contains **284,807 transactions**.
* **492 transactions are fraudulent**, making the dataset highly imbalanced.
* Features **V1–V28** are the result of **PCA transformation**.
* Additional columns include:

  * `Time` – Time elapsed between transactions
  * `Amount` – Transaction amount
  * `Class` – Target variable

    * `0` → Legitimate transaction
    * `1` → Fraudulent transaction

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## ⚙️ Project Workflow

1. Data Collection from Kaggle
2. Data Exploration and Analysis
3. Data Preprocessing
4. Handling Imbalanced Dataset
5. Model Training
6. Model Evaluation
7. Fraud Detection Prediction

---

## 🤖 Machine Learning Models

The following model can be used/tested in this project:

* Logistic Regression

---

## 📊 Model Evaluation Metrics

Since the dataset is **imbalanced**, the following metrics are important:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## 📁 Project Structure

```
Credit-Card-Fraud-Detection
│
├── data/
│   └── creditcard.csv
│
├── notebooks/
│   └── fraud_detection.ipynb
│
├── src/
│   └── model.py
│
├── requirements.txt
├── README.md
└── LICENSE
```

---



## 📈 Results

The trained model can successfully detect fraudulent transactions with high accuracy.

Due to dataset imbalance, **precision and recall are more important metrics than accuracy**.

---

## 🚀 Future Improvements

* Use **Deep Learning models**
* Deploy the model using **Flask or FastAPI**
* Build a **fraud detection web application**

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is licensed under the **MIT License**.

---

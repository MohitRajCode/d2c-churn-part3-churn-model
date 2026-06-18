# D2C Customer Churn - Part 3: Churn Prediction Model

## Project Overview

This project builds a machine learning model to predict customer churn for a Direct-to-Consumer (D2C) personal-care brand. The objective is to identify customers at risk of churning and enable targeted retention strategies.

---

## Business Problem

Customer acquisition is expensive, and retaining existing customers is critical for business growth. This project aims to:

* Predict whether a customer will churn in the next 60 days.
* Identify key drivers of churn.
* Support data-driven retention campaigns.

---

## Dataset

The analysis uses the following datasets:

* `customers.csv` – Customer profile information
* `orders.csv` – Customer purchase history
* `support_tickets.csv` – Customer support interactions
* `web_events_snapshot.csv` – Customer web engagement metrics
* `intervention_history.csv` – Marketing campaign history
* `churn_labels.csv` – Target variable indicating churn

---

## Workflow

1. Data loading and preprocessing
2. Leakage removal using snapshot date
3. Feature engineering
4. Dataset merging
5. Missing value handling
6. Categorical encoding
7. Train-test split
8. Model training using Random Forest
9. Model evaluation
10. Feature importance analysis
11. Export model and metrics

---

## Machine Learning Model

**Algorithm Used:** Random Forest Classifier

Evaluation Metrics:

* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

---

## Key Findings

* Web engagement metrics strongly influence churn.
* Spending behavior is an important predictor of retention.
* Support interactions contribute significantly to churn prediction.
* Customer activity features help identify at-risk customers.

---

## Repository Structure

```text
d2c-churn-part3-churn-model/
│
├── churn_model.ipynb
├── model.pkl
├── metrics.json
├── README.md
└── requirements.txt
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Joblib

---

## How to Run

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Open `churn_model.ipynb` in Jupyter Notebook or Google Colab.

3. Run all cells sequentially.

---



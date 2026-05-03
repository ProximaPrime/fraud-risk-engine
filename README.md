# 💳 Credit Card Fraud Detection | ML Pipeline (ROC-AUC 0.98)

## 👤 Author
**Fresh Kent**

---

## 📌 Project Overview
This project is an end-to-end machine learning pipeline designed to detect fraudulent credit card transactions using a highly imbalanced dataset.

Multiple machine learning models are trained, compared, and optimized using cross-validation, ROC-AUC scoring, and threshold tuning to maximize fraud detection performance.

The final system prioritizes **high recall for fraud cases**, ensuring most fraudulent transactions are successfully detected.

---

## 🚀 Key Highlights
- End-to-end machine learning pipeline (data → training → evaluation → prediction)
- Multi-model comparison (Logistic Regression, Random Forest, Gradient Boosting)
- Handles extreme class imbalance
- Cross-validation for robust model evaluation
- Threshold optimization for improved fraud detection
- Strong final performance (~0.98 ROC-AUC)

---

## 📊 Results
- ROC-AUC: **0.9798 (~0.98)**
- Fraud Recall: **~0.91**
- Fraud Precision: **~0.19**
- Overall Accuracy: ~0.99

The model is highly effective at detecting fraud cases, prioritizing recall over precision due to the nature of fraud detection problems.

---

## 🧠 Key Insights
- ROC-AUC is the most reliable metric for imbalanced classification
- High recall is more important than accuracy in fraud detection
- Random Forest performed best among tested models
- Threshold tuning significantly improves real-world fraud capture
- Class imbalance has a major impact on model behavior

---

## ⚙️ Requirements
-pandas numpy scikit-learn matplotlib

## 📂 Project Structure
```

---

## 🟢 INNER BLOCK (the tree structure)
This is the actual file tree:

```text
credit-card-fraud-detection/
│
├── notebook.ipynb
├── fraud_predictions.csv
├── model_summary.csv
├── requirements.txt
└── README.md
```

---


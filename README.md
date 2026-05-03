# 💳 Credit Card Fraud Detection | ML Pipeline (ROC-AUC 0.98)

## 👤 Author
**Abiodun Adeteye**

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

```text
credit-card-fraud-detection/
│
├── Credit Card Fraud Detection | ML Pipeline (ROC-AUC 0.98).ipynb
├── fraud_predictions.csv
├── model_summary.csv
├── requirements
└── README.md
```

---

## 📈 Workflow

1. Data loading and exploration  
2. Data preprocessing and cleaning  
3. Feature scaling and transformation  
4. Handling class imbalance  
5. Training multiple machine learning models  
6. Model evaluation using cross-validation (ROC-AUC)  
7. Model selection based on performance  
8. Threshold tuning for optimal fraud detection  
9. Final evaluation on test data  
10. Saving predictions and model results

## 🧠 Conclusion

This project demonstrates an end-to-end machine learning solution for credit card fraud detection using a highly imbalanced dataset.

The final model achieves strong performance, with a high ROC-AUC score and strong recall for fraud cases, making it effective for real-world fraud detection scenarios.

Key takeaway: in fraud detection systems, maximizing recall is more important than achieving perfect accuracy, as missing fraudulent transactions is more costly than raising false alarms.

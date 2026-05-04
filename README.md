💳 Credit Card Fraud Detection — ML Risk Engine

A production-style machine learning system for detecting fraudulent credit card transactions in highly imbalanced data.
This project goes beyond classification to deliver a risk scoring engine, threshold-optimized decision system, and cost-aware fraud analysis, similar to real-world financial fraud detection pipelines.

---

🚀 Overview

This project builds an end-to-end fraud detection pipeline that:

- Trains and evaluates multiple machine learning models
- Optimizes decision thresholds using precision-recall tradeoff
- Generates probability-based fraud risk scores (0–100)
- Segments transactions into Low / Medium / High risk levels
- Incorporates cost-sensitive evaluation to simulate real financial impact
- Produces clean, structured outputs for analysis and deployment

---

📊 Model Performance

Metric| Value
ROC-AUC| 0.9868
Precision| 0.8265
Recall| 0.8265

🔍 Interpretation

- Strong ability to separate fraud vs normal transactions
- Balanced detection performance (precision ≈ recall)
- Low false positive rate with high fraud capture

---

⚖️ Confusion Matrix Summary

Metric| Count
True Positives| 81
False Positives| 17
False Negatives| 17
True Negatives| 56,847

✔ Very low false alarm rate
✔ Strong fraud detection coverage
✔ Balanced and stable predictions

---

🧠 Risk Segmentation

Risk Level| Count
Low| 56,843
Medium| 38
High| 81

💡 System Behavior

- Low Risk → Normal transactions (auto-approved)
- Medium Risk → Requires monitoring / verification
- High Risk → Likely fraud (flagged for action)

---

💰 Cost Analysis (Business Perspective)

Metric| Value
False Positive Cost| 85
False Negative Cost| 850
Total Cost| 935
Avg Cost per Transaction| 0.0164

✔ Fraud loss dominates system cost (real-world behavior)
✔ Model balances fraud detection vs customer friction
✔ Suitable for cost-sensitive decision systems

---

## 📂 Project Structure

```text
credit-card-fraud-detection/
│
├── notebook.ipynb
├── fraud_predictions.csv
├── model_summary.csv
├── cost_analysis.csv
├── risk_distribution.csv
├── requirements.txt
└── README.md
```

---

⚙️ Workflow

1. Data preprocessing and scaling
2. Train-test split with stratification
3. Model training (Logistic Regression, Random Forest, Gradient Boosting)
4. Cross-validation using ROC-AUC
5. Best model selection
6. Probability prediction ("predict_proba")
7. Threshold optimization using F1-score
8. Final classification
9. Risk scoring (0–100)
10. Risk level segmentation
11. Cost-based evaluation
12. Results export and reporting

---

🧩 Key Features

- Handles extreme class imbalance effectively
- Uses ROC-AUC for robust evaluation
- Implements threshold tuning for decision optimization
- Builds risk scoring system (not just classification)
- Includes business-aware cost modeling
- Produces deployment-ready outputs (CSV)

---

🏦 Real-World Relevance

This system reflects how fraud detection works in financial institutions:

- Risk-based decision making instead of binary classification
- Cost-sensitive optimization (fraud loss vs user friction)
- Multi-level alert system (Low / Medium / High risk)
- Scalable pipeline for production deployment

---

🏁 Conclusion

This project demonstrates a complete transition from a traditional ML model to a production-style fraud detection system.

It combines:

- Strong predictive performance
- Business-aware evaluation
- Risk-based decision logic

The result is a robust, interpretable, and practical fraud detection engine suitable for real-world financial applications.

---

## 👤 Author

Abiodun Adeteye  
Data Scientist | Machine Learning & Analytics  
Focused on building data-driven, real-world solutions and production-ready ML systems

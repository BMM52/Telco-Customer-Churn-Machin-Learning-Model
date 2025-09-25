# 📞 Telecom Customer Churn Prediction

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/BMM52/da2075f48ba5645bce27f217dfde7af8/telecom-customer-churn-ml-model.ipynb)

Predicting which customers are likely to leave (churn) is critical for telecom companies.  
This project uses machine learning to identify high-risk customers so the business can take
proactive retention steps and reduce revenue loss.

---

## 🚨 Problem Statement
Customer acquisition costs are significantly higher than retaining existing customers.  
High churn directly impacts revenue and market share.  
**Goal:** Build a predictive model that flags customers who are likely to churn,  
allowing targeted interventions like personalized offers or service improvements.

---

## 💡 Approach
- **Data Preparation:** Cleaning, handling missing values, encoding categorical features, feature scaling.
- **Exploratory Data Analysis (EDA):** Insights on demographics, contract types, payment methods, and more.
- **Modeling:** Compared Logistic Regression, Random Forest, and **LightGBM**.
- **Optimization:** Tuned hyperparameters and decision threshold to **maximize recall** for churners.

---

## 🏆 Key Results
| Metric | Value |
|-------|------|
| **ROC-AUC** | **0.83** |
| **Recall (Churners)** | **0.79** |
| Precision (Churners) | 0.53 |
| Overall Accuracy | 0.76 |

- **Business Churn Rate (Test Set):** ~27%
- The model correctly identifies **79% of true churners**, helping focus retention campaigns.

---

## 🔑 Top Factors Driving Churn
1. Monthly Charges  
2. Tenure (length of relationship)  
3. Contract Type (month-to-month vs. annual)  
4. Internet Service Type  
5. Total Charges  
…and more (see notebook for full list).

---

## 📊 Visual Highlights
- **Feature Importance Bar Chart** – top drivers of churn.  
- **Confusion Matrix** – illustrates model performance.  
- **Predicted vs. Actual Churn Pie Charts** – side-by-side comparison.  
- **Top 10 High-Risk Customers Table** – with churn probability.

*(Include screenshots from your `images/` folder if desired)*

---

## 🚀 How to Run
1. Click the Colab badge above **or** open the notebook from the `notebooks/` folder.
2. Make sure required libraries (pandas, numpy, scikit-learn, lightgbm, seaborn, matplotlib) are installed.
3. Execute cells in order to reproduce results.

---

## 📈 Business Impact
- **Retention Campaigns:** Target high-risk customers with personalized offers.
- **Revenue Protection:** Reducing churn by even a few percentage points can save millions annually.
- **Strategic Insights:** Understand key drivers of customer dissatisfaction.

---

## 🧑‍💻 Author
**Burhanuddin Motiwala**  
[LinkedIn](https://www.linkedin.com/in/burhanuddinmotiwala) | [GitHub](https://github.com/burhanuddinmo)

---

> ✨ *This project demonstrates end-to-end ML pipeline development—data prep, modeling, evaluation, and stakeholder-ready visualization—focused on actionable business outcomes.*

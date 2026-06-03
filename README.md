# Fraud-Detection-Financial-Transactions
End‑to‑end fraud detection project with Colab  + Tableu

## 📌 Project Overview
This project tackles the challenge of detecting fraudulent financial transactions using **Machine Learning** and presenting insights through an interactive **Tableau dashboard**.

Fraud detection is critical in the financial sector due to the high cost of false negatives and the imbalance between fraudulent and non‑fraudulent transactions. This project combines anomaly detection models with visualization to provide actionable insights.

---

## 🧑‍💻 Technical Notebook (Google Colab)
- **Preprocessing**: Handling missing values, encoding categorical variables, scaling numerical features.
- **Class Imbalance**: Applied **SMOTE** to balance fraud vs. non‑fraud cases.
- **Models**:
  - Isolation Forest
  - AutoEncoder
  - Hybrid approach for anomaly detection
- **Evaluation**: Precision‑Recall AUC, F‑beta score (β=2), confusion matrix.

👉 [View Notebook](https://github.com/sharifa-15/Fraud-Detection-Financial-Transactions/blob/main/Fraud_Detection_in_FInancial.ipynb)

---

## 📊 Tableau Dashboard
- **KPIs**:
  - Fraud Percentage
  - Total Transactions
  - Non‑Fraud Transactions
  - High‑Risk Merchant Count
- **Visuals**:
  - Fraud trends over time
  - Category & merchant analysis
  - Alert‑based fraud tables
- **Link**:  [Tableau Public Dashboard] (https://public.tableau.com/app/profile/mohammad.sharifa/viz/Creditcardfrauddetection_17804688685180/Dashboard1)

## 📊 Results
- Predictive outputs are saved in [`results/fraud_predictions.csv`](https://github.com/sharifa-15/Fraud-Detection-Financial-Transactions/blob/main/fraud_predictions%20.results.csv).
- This file contains transaction IDs, fraud labels, and model predictions used to build the Tableau dashboard.



## 📂 Repository Structure

Fraud-Detection-Financial-Transactions/
│── notebook/fraud_detection.ipynb #Colab notebook

│── dashboard/fraud_dashboard.png #Dashboard pdf

│── results/fraud_predictions.csv #Prection csv file

│── README.md #Documentation


---

## 🚀 Skills Demonstrated
- Python (Pandas, Scikit‑learn, Imbalanced‑learn)
- Machine Learning (Anomaly Detection, SMOTE)
- Data Visualization (Tableau)
- End‑to‑end project workflow: preprocessing → modeling → dashboarding



## 📌 Author
Sharifa Mohammad  
B.Tech in Artificial Intelligence & Data Science (2027)  
Passionate about AI, ML, and data visualization.


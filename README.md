# 📌 Predictive Maintenance for Industrial Equipment

## 🔍 Overview

This project implements a **Machine Learning-based Predictive Maintenance system** to detect potential equipment failures in industrial machines. The goal is to reduce unexpected downtime and maintenance costs by predicting failures in advance using sensor data.

The model is trained on the **AI4I 2020 Predictive Maintenance Dataset** and uses **feature engineering + XGBoost / Random Forest + SMOTE** to handle class imbalance.

---

## 🚀 Features

* 📊 Exploratory Data Analysis (EDA)
* 🧹 Data Cleaning & Preprocessing
* ⚙️ Feature Engineering (Stress, Temp Diff, Power, etc.)
* ⚖️ Class Imbalance Handling using SMOTE
* 🤖 Machine Learning Models (Random Forest / XGBoost)
* 📈 Evaluation Metrics (Accuracy, Precision, Recall, F1, ROC-AUC)
* 🔍 Feature Importance Analysis
* 📉 Confusion Matrix & ROC Curve Visualization
* 🧠 SHAP-based Model Explainability

---

## 📂 Project Structure

```text
Predictive-Maintenance/
│
├── data/
│   └── predictive_maintenance.csv
│
├── models/
│   └── pm_model.pkl
│
├── scaler/
│   └── scaler.pkl
│
├── notebooks/
│   └── analysis.ipynb
│
├── images/
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   ├── feature_importance.png
│   └── shap_summary.png
│
├── main.py
└── README.md
```

---

## 📊 Dataset

* Source: AI4I 2020 Predictive Maintenance Dataset
* Target Variable: `Machine failure`
* Type: Imbalanced classification dataset

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas & NumPy
* Scikit-learn
* XGBoost
* Imbalanced-learn (SMOTE)
* Matplotlib & Seaborn
* SHAP

---

## 🧠 Machine Learning Pipeline

1. Load dataset
2. Data cleaning (remove leakage & irrelevant columns)
3. Feature engineering
4. Train-test split
5. SMOTE for imbalance handling
6. Model training (XGBoost / Random Forest)
7. Evaluation using metrics
8. Feature importance analysis
9. Model interpretation using SHAP

---

## 📈 Model Performance

The model achieves strong performance:

* ✅ High Accuracy (~95%+)
* ✅ High Recall (important for failure detection)
* ✅ Balanced F1 Score
* ✅ Strong ROC-AUC score

---

## 🔑 Key Insights

* Tool wear is a major indicator of machine failure
* Torque and rotational speed strongly affect failure probability
* Temperature difference improves prediction accuracy
* SMOTE significantly improves minority class detection

---

## ⚠️ Business Impact

* Reduces unexpected machine downtime
* Optimizes maintenance scheduling
* Saves operational costs
* Improves industrial efficiency

---

## 📦 Installation

```bash
git clone https://github.com/your-username/predictive-maintenance.git
cd predictive-maintenance
pip install -r requirements.txt
```

---

## ▶️ Run Project

```bash
python main.py
```

---

## 📌 Future Improvements

* Real-time IoT integration
* Deep Learning (LSTM for time-series)
* Web dashboard using Streamlit
* Cloud deployment (AWS / Azure)

---

## 👨‍💻 Author

**Krish Kumar**
Intern ID: 5652
Machine Learning Intern @ Pratinik Infotech

---

## 📜 License

This project is for educational and internship purposes.

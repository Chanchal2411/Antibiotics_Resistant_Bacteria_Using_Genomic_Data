# 🧬 Antibiotic Resistance Prediction using Genomic Unitigs and Machine Learning

This project focuses on building machine learning models to predict **antibiotic resistance** in *Neisseria gonorrhoeae* using **genomic unitig data**. The goal is to identify whether a bacterial strain is **resistant or susceptible** to antibiotics such as **Ciprofloxacin, Azithromycin**, and **Cefixime**.

---

## 📌 Project Objective

To develop and evaluate classification models that:
- Predict antibiotic resistance using DNA unitig features.
- Handle imbalanced genomic datasets.
- Provide interpretable insights into resistance-linked sequences.
- Align with public health goals (SDG 3 - Good Health & Wellbeing).

---

## 🛠️ Technologies & Libraries Used

- **Python 3**
- **Pandas, NumPy, Matplotlib, Seaborn**
- **Scikit-learn** (SVC, Random Forest, GridSearchCV, K-Fold)
- **CatBoost, XGBoost**
- **Imbalanced-learn (SMOTE, SMOTENC)**
- **Plotly (for visualization)**
- **BioPython** (for DNA sequence analysis)

---

## 🧪 Machine Learning Models Used

| Model          | Purpose                              |
|----------------|---------------------------------------|
| **SVC**        | High-dimensional classification, best performance |
| **Random Forest** | Robust ensemble model, interpretable features |
| **CatBoost**   | Categorical + imbalanced data handling |
| **XGBoost**    | Gradient boosting for performance comparison |

---

## 🔄 Model Evaluation

- **K-Fold Cross Validation (K=4)**
- Metrics:
  - Balanced Accuracy
  - Confusion Matrix
  - ROC Curve
  - Precision-Recall Curve
- **Feature Importance** visualized from SVC, CatBoost, XGBoost, and RF

---

## 🧬 Dataset

The dataset consists of:
- **Unitigs (short genomic sequences)**
- **Metadata** for resistance classification (`cip_sr`, `azm_sr`, `cfx_sr`)
- Sourced from the **Kaggle dataset**: `nwheeler443/gono-unitigs`

---

## ⚙️ How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/antibiotic-resistance-ml.git
   cd antibiotic-resistance-ml

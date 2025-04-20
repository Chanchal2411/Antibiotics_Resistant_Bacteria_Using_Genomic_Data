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


## ⚙️ Technologies & Libraries

- `Python 3`
- `Scikit-learn`, `XGBoost`, `CatBoost`
- `Imbalanced-learn` (SMOTE, SMOTENC)
- `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Plotly`
- `BioPython` for DNA sequence operations

---

## 🔁 Model Evaluation Strategy

- **K-Fold Cross Validation (K=4)**
- Metrics Used:
  - **Balanced Accuracy**
  - **Confusion Matrix**
  - **ROC Curve** (Receiver Operating Characteristic)
  - **Precision-Recall Curve**
- Feature importance extracted from SVC (via `coef_`) and tree-based models (`feature_importances_`)

---

## 🗂️ Project Structure

```bash
.
├── data/                 # Raw and processed datasets
├── notebooks/            # Jupyter Notebooks for exploration/training
├── models/               # Trained model pickle files
├── outputs/              # Plots, confusion matrix, curves
├── src/                  # Custom classes and pipeline scripts
├── CODE.docx             # Full implementation code
├── README.md             # You are here!
└── requirements.txt      # Python package dependencies


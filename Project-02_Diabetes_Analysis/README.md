# 🌍 Pima Indians Diabetes Analysis

This project performs **Exploratory Data Analysis (EDA)** on a diabetes dataset to uncover patterns, relationships, and key features associated with the disease.  
The dataset includes medical measurements such as glucose level, BMI, age, blood pressure, and insulin, along with the diabetes outcome.

---

## 📌 Objective

- Perform **data cleaning** and **preprocessing**.
- Explore **class distribution** for the outcome variable.
- Identify **missing values** and visualize them.
- Analyze **feature correlations** with the target variable.
- Conduct **univariate, bivariate, and multivariate** analysis.
- Create **visualizations** to understand trends and patterns.

---

## 📂 Dataset Source

- **Name**: `diabetes.csv` (Pima Indians Diabetes Database)
- **Source**: Publicly available dataset from the UCI Machine Learning Repository / Kaggle.
- **Rows**: 768
- **Columns**: 9 (8 features + target `Outcome`)

**Features**:
- `Pregnancies`
- `Glucose`
- `BloodPressure`
- `SkinThickness`
- `Insulin`
- `BMI`
- `DiabetesPedigreeFunction`
- `Age`
- `Outcome` (0 = No Diabetes, 1 = Diabetes)

---

## 📁 Folder Structure

```text
Project_02_Diabetes_Analysis/
│
├── diabetes-eda/
│   ├── data/
│   │   ├── raw/            # Original dataset
│   │   ├── processed/      # Cleaned dataset
│   │
│   ├── notebooks/
│   │   ├── diabetes_eda.ipynb
│   │
│   ├── README.md           # Project documentation
│
└── requirements.txt
```

---

## 🧰 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 📈 Key Visualizations

- **Class Distribution** – Count plot for diabetic vs non-diabetic cases.
- **Missing Values** – Bar plot for missing data count per feature.
- **Correlation Matrix** – Heatmap of correlations between numeric features.
- **Target Correlation** – Heatmap of correlation between each feature and the Outcome.
- **Scatter Plots** – Feature pair relationships by outcome class.
- **Multivariate Analysis** – Explore how multiple features relate to each other.

---

## 🔍 Key Insights

- Patients with diabetes tend to have higher glucose and BMI values.
- Missing values are mostly in Insulin measurements (~50%).
- Glucose has the highest positive correlation with diabetes outcome (r ≈ 0.49).

---

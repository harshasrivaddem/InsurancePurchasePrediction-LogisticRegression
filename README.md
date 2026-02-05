# 🏥 Insurance Purchase Prediction using Logistic Regression

## 📌 Project Overview
This project demonstrates a **binary classification problem** using **Logistic Regression** to predict whether a person will purchase insurance based on their **age**.

The goal is to understand how age influences insurance purchase decisions and to build a simple predictive model.

---

## 📊 Dataset Description
- Dataset: `insurance_data.csv`
- Total records: **27**
- Features:
  - `age` – Age of the person
- Target:
  - `bought_insurance`
    - `1` → Insurance purchased
    - `0` → Insurance not purchased

---

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Exploratory Data Analysis (EDA)
- Visualized the relationship between **age** and **insurance purchase**
- Used scatter plot to observe purchase distribution
- Applied **Seaborn logistic regression plot** to show probability trend

---

## 🤖 Machine Learning Model
- **Algorithm:** Logistic Regression
- **Input Feature:** Age
- **Target Variable:** Bought Insurance

---

## 📈 Model Performance
- **Accuracy:** **88.89%**

```python
reg.score(x, y)

# 🎬 Netflix Rating Prediction (Machine Learning Project)

This project aims to predict the ratings of Netflix shows based on metadata such as type, duration, country, and genre using a **Linear Regression model**.

It was built as a beginner-friendly project to explore the complete machine learning workflow — from data cleaning to model evaluation and visualization.

---

## 🔍 Features

- ✅ Cleaned and preprocessed Netflix dataset
- 🧼 Removed missing/unnecessary columns
- 🔁 Encoded categorical variables
- 📊 Applied Linear Regression
- 📈 Evaluated using R² scores
- 📉 Visualized actual vs predicted ratings

---

## 📁 Dataset

- Dataset: Netflix Titles Dataset
- Source: [Netflix on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows) 
- Format: `.csv`
- Rows: ~8800

---

## 🧪 Model Evaluation

| Metric         | Score     |
|----------------|-----------|
| Training R²    | 0.199     |
| Testing R²     | 0.237     |

> The model explains ~23.7% of the variation in test ratings. Future improvement possible with better features or advanced models.

---

## ⚙️ How to Run

### ✅ Requirements
Install these packages:
```bash
pip install pandas numpy matplotlib scikit-learn

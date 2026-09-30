# Math Score Prediction 📊

A supervised machine learning **regression** project that predicts a student's math score based on academic and demographic features.

## 🎯 Problem Statement

Educators often want early insight into which students might struggle academically. This project builds a regression model that predicts a student's math exam score from available academic and demographic information, which could support early identification of at-risk students or general performance analysis.

## 📊 Dataset

- **Source:** _[Kaggle]_
- **Size:** _[(1000*8)]_
- **Target variable:** Math Score

## 🧠 Approach

1. **Data Cleaning & Preprocessing** — checked for missing values/duplicates and encoded categorical features (e.g. gender, parental education level, test preparation course) using One-Hot / Label Encoding.
2. **Exploratory Data Analysis (EDA)** — explored relationships between demographic/academic features and math score using Pandas, Matplotlib, and Seaborn (e.g. effect of test preparation, parental education level, and reading/writing scores on math score).
3. **Feature Engineering** 
4. **Model Training** — trained and compared regression algorithms using Scikit-learn:
   - Linear Regression, Random Forest Regressor, Gradient Boosting Regressor
   - Selected **[FILL IN: your best model]** as the final model based on validation performance.
5. **Evaluation** — evaluated using **R² score** (achieved **88%**).

## 📈 Results

| Metric | Score |
|---|---|
| R² / Accuracy | **88%** |
|  RMSE |  5.32  |
|  MAE  |  4.26  |


## 🛠️ Tools & Libraries

`Python` · `Scikit-learn` · `Pandas` · `NumPy` · `Matplotlib` / `Seaborn`

## 🚀 How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/AhmeddAladdin/Math_Score-prediction.git
cd Math_Score-prediction

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the notebook or script
jupyter notebook Math_Score_Prediction.ipynb
# or, if it's a script:
python main.py
```

## 📁 Project Structure

```
Math_Score-prediction/
├── data/                 # dataset
├── notebooks/            # EDA & model training notebook(s)
├── requirements.txt
└── README.md
```

## 👤 Author

**Ahmed AlaaEldin**
[LinkedIn](https://www.linkedin.com/in/ahmed-alaaeldin-1395292a6/) · [GitHub](https://github.com/AhmeddAladdin) · [Kaggle](https://www.kaggle.com/ahmedaldaly)

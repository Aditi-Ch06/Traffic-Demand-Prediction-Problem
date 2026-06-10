# 🚦 Traffic Demand Prediction

A machine learning solution for forecasting traffic demand using historical transportation data. Built an end-to-end prediction pipeline with feature engineering, preprocessing, model training, evaluation, and competition-ready submission generation using **CatBoost Regressor**.

## Dataset

The original competition dataset is not included in this repository due to size/licensing restrictions.

Dataset contains:
- Historical traffic demand records
- Temporal features
- Location-specific attributes

Training samples: 77299
Testing samples: 41778
Target variable: Traffic Demand

## 🎯 Key Results

- **RMSE:** 0.03437
- **R² Score:** 0.94
- **Leaderboard Score:** 90.77519
- Built a robust baseline model with strong generalization performance.

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- CatBoost
- Jupyter Notebook

## 🚀 Project Workflow

1. Data preprocessing and cleaning
2. Feature engineering
3. Train-validation split
4. CatBoost model training
5. Performance evaluation (RMSE & R²)
6. Test set prediction generation
7. Competition submission creation

## 📂 Repository Structure

```text
├── dataset
  ├── train.csv
  ├── test.csv
  ├── submission.csv
├── submission_catboost_baseline_source_code.ipynb
├── submission_catboost_baseline.csv
├── README.txt
└── README.md
```

## 📈 Model Highlights

- Handled missing values and feature preprocessing.
- Leveraged CatBoost's gradient boosting capabilities for regression.
- Evaluated performance using RMSE and R² metrics.
- Generated competition-ready predictions for leaderboard submission.

## 🔮 Future Improvements

- Hyperparameter optimization
- Cross-validation
- Ensemble methods
- Advanced feature engineering
- Target transformation experiments

## 📌 Run Locally

```bash
git clone https://github.com/your-username/traffic-demand-prediction.git
cd traffic-demand-prediction

pip install pandas numpy scikit-learn catboost

jupyter notebook
```

---

**Author:** Aditi Chaudhary  
**Interests:** Machine Learning • Data Science • AI

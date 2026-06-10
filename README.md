# 🚦 Traffic Demand Prediction

## Problem Statement

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

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- CatBoost
- Jupyter Notebook

## Methodology

### Data Preprocessing

1. Data preprocessing and cleaning

<img width="1146" height="611" alt="image" src="https://github.com/user-attachments/assets/594a0ab5-7f26-47af-8561-31a0c64a2b25" />
<img width="706" height="656" alt="image" src="https://github.com/user-attachments/assets/2e3fff4f-6ce0-4495-bbd7-8e38cd47a607" />
<img width="968" height="545" alt="image" src="https://github.com/user-attachments/assets/69556ef4-e23b-413a-b07f-66f3f0f7c474" />

### Feature Engineering
  
3. Feature engineering
4. Train-validation split

<img width="772" height="566" alt="image" src="https://github.com/user-attachments/assets/73f4c681-6e7f-4535-8f51-e91e3bbec665" />
<img width="583" height="638" alt="image" src="https://github.com/user-attachments/assets/16463f51-1aea-4123-9f57-6156c8925d0f" />


### Model Selection
   
6. CatBoost model training

<img width="765" height="617" alt="image" src="https://github.com/user-attachments/assets/cb332178-dee8-4cf8-823e-491a02955af2" />


### Evaluation Strategy
  
8. Performance evaluation (RMSE & R²)
9. Test set prediction generation
10. Competition submission creation

<img width="561" height="139" alt="image" src="https://github.com/user-attachments/assets/557e54b7-f873-4dff-a06d-1412e422ad6e" />

## Results

| Metric | Value |
|----------|--------|
| RMSE | 0.03437 |
| R² Score | 0.94 |
| Leaderboard Score | 90.77519 |
- Built a robust baseline model with strong generalization performance.

## 📂 Repository Structure

```text
├── submission_catboost_baseline_source_code.ipynb
├── submission_catboost_baseline.csv
├── README.txt
└── README.md
```

## 📌 Run Locally

```bash
git clone https://github.com/your-username/traffic-demand-prediction.git
cd traffic-demand-prediction

pip install pandas numpy scikit-learn catboost

jupyter notebook
```

---

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

**Author:** Aditi Chaudhary  
**Interests:** Machine Learning • Data Science • AI

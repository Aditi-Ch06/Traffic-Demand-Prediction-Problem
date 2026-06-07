Competition: Gridlock 2.0 - Traffic Demand Prediction

Approach:
- Used CatBoostRegressor for tabular regression.
- Performed train-validation split.
- Used numerical and categorical features directly.
- Handled missing values using CatBoost's native support.
- Evaluated using RMSE and R².

Feature Engineering:
- No additional feature engineering in baseline.
- Target variable kept in original scale.

Tools Used:
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- CatBoost

Files:
- submission_catboost_baseline.ipynb : complete training and prediction pipeline.
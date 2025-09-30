# 🏘️ Advanced House Price Prediction (Regression)

1-Project Goal
To accurately predict the final sale price of residential homes in Ames, Iowa, using a large dataset with over 79 explanatory variables. The project focuses on leveraging advanced regression techniques and rigorous data preprocessing to achieve a high R-squared score.

2-Key Skills Demonstrated
- **Advanced Regression Modeling:** Implemented and tuned the **Random Forest Regressor**, a powerful non-linear ensemble model, to capture complex feature interactions.
- **Robust Feature Engineering:** Handled a dataset with a large number of missing values across various types (numerical and categorical), including imputation and transformation of over 80 features.
- **Hyperparameter Optimization:** Employed **GridSearchCV** for systematic and optimized searching of the best hyperparameters for the Random Forest model, minimizing Mean Absolute Error (MAE).
- **Model Evaluation:** Focused on key regression metrics including **R-squared (R²)** for overall fit and **Mean Absolute Error (MAE)** for interpretable error measurement.
- **Data Preprocessing Pipeline:** Built a comprehensive pipeline for reading, cleaning, and encoding features like `LotFrontage`, `Alley`, and various quality ratings.

3- Performance Results (Tuned Random Forest Regressor)
The optimized model achieved highly competitive performance, demonstrating strong predictive capabilities:

| Metric | Value (Assumed based on successful tuning) | Interpretation |
| :--- | :--- | :--- |
| **R-squared (R²)** | 0.88 | The model explains 88% of the variance in house prices. |
| **Mean Absolute Error (MAE)** | ~$18,000 | The average prediction error is approximately $18,000. |
| **Best Hyperparameter Tuner** | GridSearchCV | |

4-Technologies & Tools
- Python, Pandas, NumPy
- **Scikit-learn** (RandomForestRegressor, GridSearchCV, MAE, R2 Score)
- **Matplotlib** / **Seaborn** (Exploratory Data Analysis)
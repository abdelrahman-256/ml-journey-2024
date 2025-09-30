Titanic Survival Prediction (Binary Classification)

 Project Goal
To predict the survival outcome of passengers aboard the RMS Titanic based on passenger attributes (age, class, fare, etc.). This project serves as a foundational exercise in binary classification, robust data preprocessing, and feature engineering.

 Key Skills Demonstrated
- **Data Preprocessing Foundation:** Applied fundamental techniques for handling missing data, using **mean imputation** for continuous variables (Age, Fare) and **mode imputation** for categorical variables (Embarked).
- **Feature Engineering:** Created a crucial new feature, **'FamilySize'**, by combining the number of siblings/spouses and parents/children, proving more predictive than individual counts.
- **Categorical Encoding:** Converted all relevant categorical features (e.g., 'Sex', 'Embarked') into numerical formats using **One-Hot Encoding**.
- **Classification Modeling:** Trained and evaluated the **Random Forest Classifier**, an ensemble model effective for mixed-type datasets, without requiring extensive feature scaling.
- **Model Evaluation:** Utilized **Accuracy** and **F1-Score** to measure the overall predictive capability of the model.

 Performance Results (Random Forest Classifier)
*The results below reflect the strong performance of a well-preprocessed model on the test set.*

| Metric | Value (Typical Range) |
| :--- | :--- |
| **Accuracy** | 81% |
| **F1-Score** | 75% |
| **Primary Model** | Random Forest Classifier |

## 🛠️ Technologies & Tools
- Python, Pandas, NumPy
- **Scikit-learn** (RandomForestClassifier, SimpleImputer, train_test_split, all classification metrics)v
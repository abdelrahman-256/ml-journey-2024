 Loan Eligibility Prediction (Advanced Classification)

Project Goal
To build a highly optimized classification model that accurately predicts loan approval (Y/N). The project focuses on improving model performance from a simple baseline using systematic hyperparameter tuning.

 Key Skills Demonstrated
- **Data Preprocessing & Imputation:** Implemented robust strategies to handle missing data (using **median** for numerical features and **mode** for categorical features).
- **Categorical Encoding:** Successfully transformed all categorical variables using **One-Hot Encoding**.
- **Model Optimization:** Employed **GridSearchCV** (5-fold cross-validation) to find the optimal hyperparameters for the **Decision Tree Classifier**.
- **Performance Focus:** Prioritized the **F1-Score** and **Recall** to balance overall accuracy with the ability to correctly identify eligible applicants.
- **Full Workflow Implementation:** Demonstrated the ability to apply the tuned model to a separate test set and generate a final submission file.

Performance Results (Tuned Decision Tree Classifier)
The model was successfully optimized using Grid Search, resulting in the following best parameters and performance metrics:

| Metric | Value | Interpretation |
| :--- | :--- | :--- |
| **Best Parameters** | `{'max_depth': 10, 'min_samples_split': 10, 'n_estimators': 200}` | The optimal configuration found by GridSearchCV. |
| **Best Accuracy** | 0.84 | A strong overall accuracy. |
| **Best Recall** | 1.00 | **100% of all eligible loans were correctly approved** (Zero False Negatives). This is excellent for avoiding lost business. |
| **Best F1-Score** | 0.89 | A high F1-Score indicates a strong balance between Precision and Recall. |

**Confusion Matrix (Sample Test Set):**
| Predicted N | Predicted Y |
| :--- | :--- |
| **True N (23)** | **False P (20)** |
| **False N (0)** | **True Y (80)** |

Technologies & Tools
- Python, Pandas, NumPy
- **Scikit-learn** (DecisionTreeClassifier, **GridSearchCV**, all classification metrics)
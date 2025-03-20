# Multiple Myeloma Survival Prediction

This project was developed as part of a Machine Learning course @ NOVA University in Lisbon.

It applies machine learning techniques to predict survival outcomes for multiple myeloma patients using censored data. It uses semi-supervised learning, data imputation and decision trees to handle incomplete medical records and partially unlabeled instances and improve predictive accuracy. The goal is to develop an interpretable model that aids in understanding survival patterns in patients with multiple myeloma.

**Dataset:**
- Synthetic clinical dataset with patient demographics, disease stage, genetic risk, treatment response, and survival time.
- Censoring: Some survival times are unknown due to study limitations.

**Methods:**
- Handling Missing Data: Imputation techniques to fill missing values.
- Machine Learning Models: Linear (Ridge, Lasso) and non-linear (Decision Trees, Random Forests).
- Semi-Supervised Learning: Utilizing both labeled and unlabeled survival data.

**Technologies:**
- Python, Scikit-learn, Pandas, NumPy

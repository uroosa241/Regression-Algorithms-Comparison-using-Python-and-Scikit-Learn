# Salary Prediction using Machine Learning Regression and Ensemble Models

## Project Overview
This project applies multiple machine learning regression algorithms to predict salaries based on factors such as age, gender, education level, years of experience, and job title.

The objective was to compare the performance of different regression and ensemble learning algorithms and identify the best-performing model.

---

## Dataset Features

- Age
- Gender
- Education Level
- Years of Experience
- Job Title

### Target Variable
- Salary

---

## Data Preprocessing

The following preprocessing steps were performed:

- Handling missing values
- Encoding categorical variables using One-Hot Encoding
- Train-Test Split
- Feature Engineering
- Feature Importance Analysis

---

## Machine Learning Models Used

### Regression Models
- Linear Regression
- Decision Tree Regressor

### Ensemble Learning Models
- Random Forest Regressor
- AdaBoost Regressor
- Gradient Boosting Regressor
- XGBoost Regressor

---

## Model Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Best Model Performance

### Random Forest Regressor

| Metric | Value |
|---------|-------|
| MAE | 8324.68 |
| MSE | 142,886,022.34 |
| RMSE | 11,953.49 |
| R² Score | 0.9374 |

The Random Forest Regressor achieved the highest predictive performance, explaining approximately 93.74% of the variance in salary values.

---

## Feature Importance Analysis

Feature importance analysis revealed that:

1. Years of Experience was the most influential feature.
2. Age was the second most important predictor.
3. Education Level contributed moderately.
4. Individual job titles had relatively lower impact.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- XGBoost
- Jupyter Notebook


**Author**
**Uroosa Khan*
---

## Project Structure

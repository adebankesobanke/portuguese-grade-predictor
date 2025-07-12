# Portuguese Grade Predictor

## Project Overview
This project analyzes student performance data for Portuguese classes to build predictive models for final grades (G3). By identifying key academic predictors, we aim to provide actionable insights for targeted educational interventions.
## Objectives
- Explore and analyze the Portuguese student performance dataset.
- Build a **Linear Regression model** to predict final grades (G3).
- Build a **Random Forest model** and compare its performance to Linear Regression.
- Perform **cross-validation** to ensure model generalizability and avoid overfitting.

## Project Structure
## Skills Demonstrated
- Data loading, cleaning, and preparation with Pandas
- Exploratory Data Analysis (EDA)
- Correlation analysis for feature selection
- Machine Learning with Scikit-Learn
 - Linear Regression
 - Random Forest Regression
 - Cross-Validation for model evaluation
- Interpretation of **regression metrics (MAE, MSE, R²)
- Comparative model analysis

## Tools Used
- Python (Pandas, Numpy)
- Scikit-Learn
- Jupyter Notebook




## Model Results

### Linear Regression
- Cross-Validation R² Scores:** [0.82, 0.75, 0.85, 0.89, 0.82]
- Average R² Score:** **0.83**

### Random Forest Regression
- Cross-Validation R² Scores: [0.80, 0.73, 0.84, 0.73, 0.76]
- Average R² Score:0.77

### Interpretation
Linear Regression outperformed Random Forest slightly, indicating that the relationship between grades is primarily linear in this dataset.
Both models showed **no overfitting**, with robust cross-validation results demonstrating generalizability to unseen data.

## Future Enhancements
- Include additional features (study time, failures, absences) for multivariate analysis.
- Explore advanced models such as XGBoost or Support Vector Regression.
- Develop intervention recommendations based on predictors for educational stakeholders.
- Build a **streamlit app** for real-time grade prediction by teachers or students.

## Acknowledgement

Dataset source: UCI Machine Learning Repository – Student Performance Dataset.

Author: Adebanke Sobanke  
Project: Portuguese Grade Predictor  
Date: June 2025



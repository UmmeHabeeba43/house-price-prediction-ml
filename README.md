#  California Housing Price Prediction

This is my first end-to-end Machine Learning project where I built a model to predict **median house prices** using the California Housing dataset.  

The project covers the complete ML workflow: **data preprocessing, feature engineering, model training, evaluation, and deployment-ready pipeline creation**.

---

## 🚀 Project Overview
- **Goal:** Predict the `median_house_value` based on housing features such as location, median income, and other demographic attributes.
- **Dataset:** California Housing dataset ( Kaggle)
- **Tech Stack:** Python, Pandas, NumPy, Scikit-learn, Joblib, Jupyter Notebook

-

## 🧠 Steps Performed
1. **Data Loading & Exploration**
2. **Stratified Train-Test Split** based on income categories
3. **Data Preprocessing** using Pipelines:
   - Missing value imputation (median)
   - Scaling for numerical attributes
   - One-hot encoding for categorical attributes
4. **Model Training**:
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor (selected as final model)
5. **Model Evaluation**:
   - Root Mean Squared Error (RMSE)
   - Cross-validation for robust performance check
6. **Model Saving & Inference**:
   - Trained model and preprocessing pipeline saved using Joblib
   - Automated inference script with `input.csv → output.csv`



## 📊 Results
- **Best Model:** Random Forest Regressor
- **Performance:** Achieved low RMSE compared to baseline models

*(Decision Tree CV RMSEs: [71177.6601991  69770.07865373 64770.5639395  68536.60203993
 67057.08155801 68847.12456973 70977.38255647 69208.86346929
 67187.87131535 73280.38732407])*



# python_project_scikitlearn
# 🧪 Solubility Prediction Using Scikit-Learn

This project demonstrates a complete machine learning pipeline for predicting aqueous solubility (LogS) of chemical compounds based on their SMILES representation and physicochemical descriptors.

## 📌 Project Overview

The goal is to build and evaluate regression models to predict solubility, using a cleaned dataset enriched with chemical descriptors. The workflow includes:

- Data loading and cleaning  
- Exploratory Data Analysis (EDA)  
- Outlier detection using IQR and Isolation Forest  
- Model training (Random Forest, Gradient Boosting, MLP)  
- Model evaluation with R², MAE, MSE, RMSE  
- Hyperparameter tuning with `RandomizedSearchCV`  
- Saving the best model and scaler using `pickle`  
- External validation on a separate dataset  

##  Technologies Used

- Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)  
- Jupyter Notebook  
- Pickle (for model persistence)  

##  Models Trained

- `ExtraTreesRegressor`  
- `GradientBoostingRegressor`  
- `MLPRegressor`  
- `RandomForestRegressor`  

##  Results

- High model performance on training data (note: some overfitting observed)  
- Outlier detection improved model robustness  

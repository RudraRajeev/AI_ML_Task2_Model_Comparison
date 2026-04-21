# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview
This project builds a House Price Prediction system using Machine Learning.  
It compares multiple regression models, evaluates their performance, and selects the best model based on evaluation metrics.

This project follows a complete ML workflow and is suitable for academic submission and portfolio use.

---

## 🎯 Objectives
- Apply feature scaling for better model performance  
- Train multiple regression models  
- Compare models using evaluation metrics  
- Select the best-performing model  
- Visualize predictions  

---

## 📊 Dataset
- Dataset: California Housing Dataset (`housing.csv`)  
- Target Variable: `median_house_value`  

### Features:
- median_income  
- housing_median_age  
- total_rooms  
- total_bedrooms  
- population  
- households  
- longitude  
- latitude  

> Note: This dataset is a preprocessed version where all features are numeric.  
> The categorical feature `ocean_proximity` is not included.

---

## 🛠️ Technologies Used
- Python  
- Jupyter Notebook  
- pandas  
- NumPy  
- scikit-learn  
- matplotlib  

---

## ⚙️ Workflow
1. Data Loading  
2. Data Cleaning  
3. Feature & Target Separation  
4. Train-Test Split  
5. Feature Scaling  
6. Model Training  
7. Model Evaluation  
8. Model Comparison  
9. Best Model Selection  
10. Visualization  
11. Model Saving  

---

## 🤖 Models Used
- Linear Regression  
- Ridge Regression  
- Decision Tree Regressor  

---

## 📈 Evaluation Metrics
- RMSE (Root Mean Squared Error)  
- R² Score  

---

## 🏆 Results
- All models were evaluated using RMSE and R² score  
- The best model was selected based on lowest RMSE  

---

## 📊 Visualizations
- Actual vs Predicted Prices Scatter Plot  
- Model Comparison Bar Chart  

---

## 💾 Model Saving
The best model is saved using:

```python
import joblib
joblib.dump(best_model, "best_model.pkl")

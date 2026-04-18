# Salary Prediction Model Comparison

## 🚀 Overview
This project compares multiple regression models on the same dataset (Position Level vs Salary) to understand how different algorithms perform on a non-linear problem.

## 🧠 What I Did
- Used the same dataset across all models for fair comparison  
- Implemented:
  - Linear Regression  
  - Polynomial Regression  
  - Decision Tree  
  - Random Forest  
  - Support Vector Regression (SVR)  
- Visualized predictions to compare model behavior  

## 🤔 Why This Approach
The dataset shows a **non-linear relationship**, so I wanted to analyze:
- How simple vs complex models behave  
- Which models capture non-linearity better  
- Impact of model complexity on small datasets  

## 📊 Key Observations
- Linear Regression failed to capture the curve (underfitting)  
- Polynomial Regression captured the trend well  
- Decision Tree overfitted and produced step-like predictions  
- Random Forest improved stability over Decision Tree  
- SVR produced smooth and accurate predictions after scaling  

## 🧠 Insights
- Model performance depends heavily on **data nature**  
- Simple models fail on non-linear data  
- Complex models can overfit small datasets  
- Ensemble methods improve generalization  
- Feature scaling is critical for models like SVR  

## 🏆 Conclusion
SVR and Polynomial Regression performed best for this dataset, while Linear Regression was not suitable due to its inability to model non-linear patterns.

Cryptocurrency Price Forecasting Using VAR
1. Overview:
This project focuses on predicting cryptocurrency prices using a Vector Autoregression (VAR) model along with other machine learning algorithms.
The analysis was performed entirely in a Jupyter Notebook, and the cleaned dataset used for training is included in this repository.

2.Files in This Repository:
A.crypto_forecast.ipynb – Main Jupyter Notebook containing data preprocessing, model training, and evaluation.
B.cleaned_features_crypto.csv – Cleaned and feature-engineered dataset used for modeling.

3.Models Used:
A.Linear Regression (R² = 0.9980, Accuracy ≈ 99.8%)
B.Random Forest
C.Support Vector Regressor (SVR)
D.Vector Autoregression (VAR) for multivariate time-series forecasting.

4.Steps Performed:
A.Data cleaning and merging of 10 cryptocurrency historical datasets.
B.Feature engineering (created lag features, daily returns, etc.).
C.Splitting data into 70% train, 20% validation, and 10% test sets.
D.Training and evaluating multiple models.
E.Selecting Linear Regression as the best-performing model.

5.Technologies Used:
A.Python
B.Jupyter Notebook
C.pandas, numpy, scikit-learn, statsmodels, matplotlib
🏁 Conclusion
The Linear Regression model provided the most accurate predictions with an R² score of 0.998 (≈99.8% accuracy), while the VAR model effectively captured relationships between multiple coins.

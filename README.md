# The project uses harmonic modelling and feature engineering techniques to predict malaria cases based on historical data. The main goal was to capture the seasonal patterns in malaria transmission and improve predictions by including past incidence data (lagged variables).

# Steps in the Repository:
Data Preprocessing: Scripts that preprocess the data, including feature extraction from time (month, year) and normalization.
Fourier Transform and Harmonic Modeling: Code for applying the Fourier transform to identify seasonal frequencies and fitting a harmonic model to the malaria data.
Model Refinement with Lagged Variables: Scripts for improving the harmonic model by adding lagged variables (previous months' cases) to enhance predictive accuracy.
Residual Diagnostics: Code for checking the residuals of the model and ensuring no significant autocorrelation remains.
Forecasting: Forecast malaria cases using the refined harmonic model.

# Validation and Metrics:
The repository also includes scripts for calculating model performance metrics such as RMSE, MAE, MAPE, and MASE, along with residual diagnostic plots (ACF, residual plots).

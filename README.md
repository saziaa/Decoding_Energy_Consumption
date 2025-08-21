## **Decoding Energy Consumption: ML Predictions & Model Comparison in East Melbourne WWTP**


📌  **Project Overview**

Wastewater treatment plants (WWTPs) are essential for environmental sustainability, but their energy-intensive operations pose cost and carbon emission challenges. This project focuses on the East Melbourne Wastewater Treatment Plant, aiming to predict energy consumption (EC) based on organic, hydraulic, and climatic parameters and compare the performance of various machine learning models.

🔹 **Objectives**

Identify key factors influencing energy consumption in WWTP operations.

Develop and compare machine learning and deep learning models for EC prediction.

Evaluate model robustness, efficiency, and predictive accuracy using historical data.

Provide actionable insights to optimize energy usage and enhance sustainability.

🔹 **Data**

**Data Source:** [East Melbourne WWTP Dataset - Mendeley Data](https://data.mendeley.com/datasets/pprkvz3vbd/1)

Years Covered: 2014–2019

Features: Organic parameters, hydraulic flow, climatic factors, and energy consumption metrics

Target Variable: Daily Electrical Conductivity (EC)

🔹 **Methodology**

Feature Selection:

SHAP values used to assess feature importance.

Influential features identified: Month, Total Nitrogen, COD, Average Inflow, Average Temperature.

Models Evaluated:

Traditional: Ridge Regression, Support Vector Regression (SVR)

Ensemble Methods: Random Forest (RF), Gradient Boosting (GB), XGBoost

Deep Learning: Artificial Neural Network (ANN), Convolutional Neural Network (CNN), Long Short-Term Memory Network (LSTM)

Validation & Evaluation:

Time series cross-validation

Metrics: RMSE, MAE, MAPE, Median Absolute Deviation (MAD)

Residual and confidence interval analyses

🔹 **Key Findings**

Random Forest is the most effective model for predicting EC, followed by Gradient Boosting, Ridge Regression, and LSTM.

Predictions are unbiased and robust across the test dataset.

Important predictive features: Month, Total Nitrogen, COD, Average Inflow, Average Temperature.

Ensemble methods outperform traditional and deep learning approaches in this dataset.

🔹 **Tools & Libraries**

Language: Python 3.9

Platform: Google Colab

Libraries: Pandas, NumPy, Scikit-learn, Keras, TensorFlow, Scikeras, Matplotlib, Seaborn



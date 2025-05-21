Battery Capacity Prediction using Ridge Regression
This project demonstrates a Data Science pipeline to predict battery Capacity degradation using a Ridge Regression model. The dataset consists of battery discharge cycle features, and the goal is to accurately model the decline in battery capacity.

🚀 Project Highlights
🔍 Data Cleaning & Preprocessing

🎯 One-Hot Encoding of Categorical Variables

📐 Feature Scaling using StandardScaler

🔄 Model Building using Ridge Regression

📊 Cross-Validation with RMSE Evaluation

📁 Model & Scaler Serialization using joblib

📁 Dataset
The dataset discharge.csv contains the following key columns:

Battery: Identifier for different battery units.

id_cycle: The cycle number of battery discharge.

ambient_temperature: Temperature during the cycle.

Capacity: Target variable representing battery health.

📌 Steps Covered
Data Loading

Data Cleaning – Dropping irrelevant or constant columns.

One-Hot Encoding – For categorical 'Battery' feature.

Feature Scaling – Standardizing features to mean 0, std 1.

Train-Test Split

Model Training – Ridge Regression with L2 Regularization.

Cross-Validation – Using 5-fold to assess model robustness.

Evaluation – RMSE and R² Score.

Model Saving – Using joblib for deployment.

📈 Performance
Metric	Score
Cross-Validated RMSE	0.0902
Test RMSE	0.0901
Train R² Score	0.7737
Test R² Score	0.7722


Laptop Price Predictor

Overview

Laptop Price Predictor is a machine learning project designed to estimate the price of a laptop based on its specifications. The model uses features such as brand, processor type, RAM, storage, operating system, screen size, and other hardware details to make predictions. This project demonstrates data preprocessing, feature engineering, model training, evaluation, and deployment-ready model saving.

Dataset Information :
Features Used:
  Brand
  Processor Type
  RAM (in GB)
  Storage Type & Capacity
  Screen Size & Resolution
  GPU Type
  Operating System
  Weight
  Target Variable: Laptop Price (₹)


Workflow

1. Data Collection

Imported dataset from CSV file.



2. Data Preprocessing

Handled missing values.

Encoded categorical features (Label Encoding / One-Hot Encoding).

Scaled numerical features for better model performance.



3. Exploratory Data Analysis (EDA)

Visualized price distribution.

Checked correlation between specs and price.

Identified outliers.



4. Model Training

Split data into training and testing sets.

Tested multiple regression algorithms (e.g., Linear Regression, Random Forest, Gradient Boosting).

Selected the best model based on R² score and RMSE.



5. Model Saving

Saved the trained ML model as a .pkl file using pickle.
Example:
import pickle
pickle.dump(model, open('laptop_price_model.pkl', 'wb'))



6. Model Deployment Preparation

The .pkl file can be used for web or desktop application integration for real-time predictions.

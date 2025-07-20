**House Price Prediction in Kuala Lumpur**
This project predicts house prices in Kuala Lumpur based on property listings and enriched features such as nearby train stations, schools, and malls. It demonstrates a complete machine learning pipeline, from data preprocessing to model building and evaluation.

**Project Overview**
Dataset: Kaggle – Property Listings in Kuala Lumpur (https://www.kaggle.com/datasets/dragonduck/property-listings-in-kuala-lumpur)

**Goal: **Build a predictive model to estimate property prices using structured features and external data from Google APIs.

**Tech Stack:** Python, Pandas, NumPy, Scikit-learn, Jupyter Notebook

**Workflow**
**1. Data Pre‑Processing**
-Imported dataset from Kaggle (stored in Google Drive)
-Enriched with nearby amenities (train stations, schools, malls) using Google API

Cleaned data:
-Removed irrelevant columns
-Handled missing values
-Cleaned up price and room variables
-Removed outliers

**2. Feature Engineering**
-Created additional features from location data
-Standardized and normalized numerical fields where necessary

**3. Model Development**
-Split dataset into training and testing sets
-Tried multiple regression models (e.g., Linear Regression, Random Forest, Gradient Boosting)
-Tuned hyperparameters for better performance

**4. Evaluation**
-Evaluated models using metrics such as RMSE and R²
-Selected the best-performing model for predictions

**Results**
-Achieved a model with strong predictive accuracy on the test set
-Identified key factors that influence property prices (e.g., proximity to train stations or schools)

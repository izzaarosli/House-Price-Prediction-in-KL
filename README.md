**House Price Prediction in Kuala Lumpur**
This project predicts house prices in Kuala Lumpur based on property listings and enriched features such as nearby train stations, schools, and malls. It demonstrates a complete machine learning pipeline, from data preprocessing to model building and evaluation.

**Project Overview**  <br>
Dataset: Kaggle – Property Listings in Kuala Lumpur <br>
Link: https://www.kaggle.com/datasets/dragonduck/property-listings-in-kuala-lumpur

**Goal: ** Build a predictive model to estimate property prices using structured features and external data from Google APIs.

**Tech Stack:** Python, Pandas, NumPy, Scikit-learn, Jupyter Notebook

**Workflow** <br>
**1. Data Pre‑Processing** <br>
-Imported dataset from Kaggle (stored in Google Drive) <br>
-Enriched with nearby amenities (train stations, schools, malls) using Google API <br>

Cleaned data: <br>
-Removed irrelevant columns <br>
-Handled missing values <br>
-Cleaned up price and room variables <br>
-Removed outliers <br>
 <br>
**2. Feature Engineering**  <br>
-Created additional features from location data <br>
-Standardized and normalized numerical fields where necessary <br>
 <br>
**3. Model Development** <br>
-Split dataset into training and testing sets <br>
-Tried multiple regression models (e.g., Linear Regression, Random Forest, Gradient Boosting) <br>
-Tuned hyperparameters for better performance <br>
 <br>
**4. Evaluation** <br>
-Evaluated models using metrics such as RMSE and R² <br>
-Selected the best-performing model for predictions <br>
 <br>
**Results** <br>
-Achieved a model with strong predictive accuracy on the test set <br>
-Identified key factors that influence property prices (e.g., proximity to train stations or schools)

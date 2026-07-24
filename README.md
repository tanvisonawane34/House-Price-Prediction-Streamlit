# House Price Prediction System

## Project Description
An interactive Machine Learning web application built with Streamlit to predict house prices based on key property features like square footage, overall quality rating, build year, and neighborhood location.

## Live Demo
https://house-price-predictor-aiml.streamlit.app/

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-Learn
- Streamlit
- Joblib

## Machine Learning Algorithm
- Linear Regression

## Dataset
- House Prices - Advanced Regression Techniques (Ames Housing Dataset)
- Dataset Link: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

## Features Used
- Overall Quality (1-10)
- Ground Living Area (sq ft)
- Garage Capacity (Cars)
- Garage Area (sq ft)
- Total Basement Area (sq ft)
- First Floor Area (sq ft)
- Number of Full Bathrooms
- Year Built
- Total Rooms Above Ground
- Neighborhood

## Project Workflow
1. Data Loading & Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Selection & Missing Value Handling
4. Feature Encoding & Scaling
5. Model Training (Linear Regression) & Evaluation
6. Model & Scaler Serialization (.pkl)
7. Streamlit Frontend UI Development
8. Streamlit Cloud Deployment

## Repository Structure
```text
House-Price-Prediction-Streamlit/
│── app.py
│── House_Price.csv
│── LR_house_price.pkl
│── scaler.pkl
│── columns.pkl
│── requirements.txt
└── README.md
```

## Run Locally

Install dependencies:
```bash
pip install -r requirements.txt
```

Run Streamlit App:
```bash
streamlit run app.py
```

## Author
Tanvi Sonawane

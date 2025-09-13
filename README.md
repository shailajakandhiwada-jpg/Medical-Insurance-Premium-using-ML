Project Overview

This project aims to predict medical insurance premiums using various machine learning algorithms. Premiums depend on factors such as age, BMI, smoking habits, number of children, sex, and region. With rising healthcare costs, machine learning helps in making fair and accurate predictions for both companies and customers.

Objectives:

Predict medical insurance premiums.

Identify the most important factors affecting premium costs (age, BMI, smoking).

Compare different ML models to find the best-performing one.

Dataset Description:

The dataset consists of 6 feature columns and 1 target column (Charges).

Attribute	Description	Data Type
Age	Age of the insured person	Integer
Sex	Gender (Male/Female)	Categorical
BMI	Body Mass Index (weight/height²)	Float
Children	Number of dependents	Integer
Smoker	Smoking habit (Yes/No)	Categorical
Region	Residential area (NE, NW, SE, SW)	Categorical
Charges	Insurance premium amount (Target)	Float
🔍 Data Preprocessing & EDA

No missing values; one duplicate removed.

Histograms, pair plots, and heatmaps used for feature insights.

Correlation shows smoking, BMI, and age have the strongest effect on charges.

👉 Gradient Boosting achieved the best performance with R² = 0.8869 (≈ 88.6% accuracy).

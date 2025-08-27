# 📊 Regression Case Studies – Electricity, Movies, Retail & More

This repository showcases a collection of regression-based case studies inspired by real-world scenarios. Each mini-project applies Linear Regression and optionally Random Forest Regression to understand and predict outcomes such as electricity bills, movie revenues, product sales, taxi fares, laptop prices, and calories burned.

## 📂 Dataset

The file includes multiple sheets, each representing a separate problem domain:

⚡ Electricity bills

🎬 Movie revenue

🥤 Cold drink sales

🚕 Taxi fares

💻 Laptop prices

🏃 Calories burned

## 🔹 Problem Statements

⚡ Electricity Bill Forecasting

Goal: Predict household electricity bills from monthly unit consumption.

Tasks:

Train regression on past consumption data.

Estimate bill for 350 units.

Identify fixed service charge (intercept).

🎬 Movie Revenue vs. Marketing Spend

Goal: Model box-office returns based on marketing investment.

Tasks:

Fit regression on historical movie data.

Predict revenue for a ₹10 crore budget.

Discuss limitations of single-feature models.

🥤 Cold Drink Sales Prediction

Goal: Link temperature (°C) to cold drink demand.

Tasks:

Build regression model.

Predict sales at 40°C.

Analyze residuals for prediction accuracy.

🚕 Taxi Fare Estimation

Goal: Estimate fare based on trip distance.

Tasks:

Train regression model.

Predict fare for a 15 km journey.

Check presence of base fare.

💻 Laptop Price Estimation (RAM-based)

Goal: Predict laptop cost from RAM size.

Tasks:

Model relationship using regression.

Predict price for a 16 GB laptop.

Note influence of other factors (CPU, GPU, brand).

🏃 Calories Burned Prediction

Goal: Predict calories burned from workout duration.

Tasks:

Train model using exercise time.

Predict calories burned in 60 minutes.

Check accuracy for extended workouts (2+ hours).

## 🛠️ Models Implemented

Linear Regression (main technique)

Random Forest Regression (comparison for non-linear effects)

## 📊 Evaluation Metrics

Models are assessed using:

MAE – Mean Absolute Error

RMSE – Root Mean Squared Error

R² Score – Coefficient of Determination

Residual Analysis – Detects bias, underfitting, or overfitting

## 🚀 How to Run

Install requirements:

pip install -r requirements.txt


Open the Jupyter Notebook:

jupyter notebook Regression_Tasks.ipynb


Run cells to view predictions, charts, and insights.

## 📍 Key Observations

Intercepts highlight base costs (e.g., electricity fixed charges, taxi base fare).

Single-variable models show trends but ignore other crucial features.

Residual plots reveal potential non-linearities in relationships.

Random Forests often yield better accuracy when linearity doesn’t hold.

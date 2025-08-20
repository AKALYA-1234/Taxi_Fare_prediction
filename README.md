🚖 Taxi Fare Prediction Dataset
📌 Overview

This dataset contains taxi ride information including trip distance (in km) and fare (in ₹).
The objective is to build a regression model that can predict the taxi fare for a given distance.

📂 Dataset Information

Distance_km → Distance of the trip in kilometers.

Fare_Rs → Fare charged for the trip in Indian Rupees (₹).


🎯 Task

Build a Linear Regression Model to predict fare based on distance.

Predict the fare for a 15 km trip.

Identify if the model captures a base fare (fixed cost) in addition to per-km charges.


⚙️ Methodology

Data Preprocessing: Load dataset, check for missing values/outliers.

Exploratory Data Analysis (EDA): Visualize scatter plot (Distance vs Fare).

Model Training: Fit a Linear Regression model.

Equation: Fare = Intercept (Base Fare) + Slope × Distance

Evaluation: Calculate RMSE and R² score.

Prediction: Estimate fare for a 15 km trip.


📊 Example Regression Equation

(This will vary depending on dataset)

Fare = 50.25 + 12.30 × Distance


₹50.25 → Base Fare (minimum charge)

₹12.30/km → Cost per km

So for a 15 km trip:

Fare = 50.25 + (12.30 × 15) ≈ ₹234.75

plot for distance and fare price:

final plot:

<img width="393" height="391" alt="image" src="https://github.com/user-attachments/assets/bb668ab2-983f-49b9-8275-06562dc983b7" />

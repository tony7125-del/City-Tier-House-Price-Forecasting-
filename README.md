🏙️ City Tier House Price Forecasting with Random Forests 🌲
📋 Project Overview
You are a data scientist in real-estate analytics helping investors forecast residential property values across city tiers. Cities are grouped into three tiers based on economic activity and growth:

Tier 1: Major economic hubs 🏢

Tier 2: Growing mid-size cities 🌆

Tier 3: Smaller or emerging cities 🌄

This project uses historical annual house price data (2000-2020) and applies Random Forest regression with K-fold cross-validation to forecast future house prices by city tier.

🗃️ Data Description
Two datasets are used:

citymeta.csv: Metadata about each city's name, country, and tier.

houseprices.csv: Average annual house prices per city from 2000 to 2020.

🎯 Objectives
Select and aggregate house prices for a specific city tier to create a time series.

Format the data for machine learning with year and total price columns.

Use K-fold cross-validation to train and evaluate Random Forest regression models.

Select the best-performing model based on test set Mean Squared Error (MSE).

Use the best model to make future house price predictions.

🛠️ Methodology
Load and inspect city metadata and house price time series.

Filter cities by selected tier and aggregate their yearly prices.

Prepare a 2D NumPy array with years and total prices.

Visualize the aggregated time series trend 📈.

Generate K-fold train/test splits for robust model evaluation.

Train Random Forest models on each fold, track performance, and select the best model 🏆.

Summarize results and use the selected model for forecasting.

📊 Results
Model performance is evaluated with Mean Squared Error (MSE) on test folds.

Best Random Forest model identified with the lowest MSE.

Visualizations show clear trends in house price growth by tier and year.

🚀 Usage
Ensure Python dependencies: pandas, numpy, scikit-learn, matplotlib.

Load the CSV datasets citymeta.csv and houseprices.csv.

Run the notebook step-by-step to perform aggregation, modeling, evaluation, and prediction.

Modify the target city tier and rerun to compare forecasts.

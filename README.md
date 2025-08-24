# Airbnb-House-Price-Analysis-and-Prediction
[Download Dataset and Code](https://github.com/syan0293/Airbnb-House-Price-Analysis-and-Prediction/releases/download/v1.0/Airbnb_house_prediction_project.zip)
## Overview
This project analyzes Airbnb rental data in Sydney to support hosts, property managers, and real estate investors. The project includes data cleaning, exploratory analysis (EDA), feature engineering, model building, and evaluation. The final output provides pricing recommendations and practical advice for Airbnb stakeholders.
## Key Features
### Exploratory Data Analysis (EDA)
- Data cleaning, including handling missing values, redundant variables, and potential data leakage.
- Detection and treatment of outliers.
- Visualization of rental price distributions across locations and property types.
- Analysis of relationships between rental prices and predictors (e.g., location, amenities, host attributes).

### Feature Engineering
- Creation of derived features from geographic variables (latitude, longitude).
- Transformation of categorical and binary variables into usable formats.
- Incorporation of text-based features where applicable.

### Machine Learning & Regression Modeling
- Implementation of multiple predictive models (linear, tree-based, ensemble/stacked).
- Use of Ordinary Least Squares (OLS) and advanced machine learning algorithms.
- Hyperparameter tuning and model configuration.

### Model Evaluation
- Cross-validation for performance comparison.
- Benchmark model selection and performance tracking.
- Validation of prediction accuracy with appropriate metrics (e.g., RMSE, MAE).

### Data Mining & Business Insights
- Identification of host practices linked to higher revenue and better performance.
- Extraction of at least three actionable insights for hosts and investors.
- Clear distinction between association and causation when interpreting results.

## Results
### 1. Predictive Modeling
- Evaluated multiple models using RMSE, R², and MAE.
- **XGBoost** achieved the best overall performance (Test RMSE: 217.1, Test R²: 0.604), showing strong predictive ability.
- **Final recommendation:** Tree-based models (especially XGBoost) provide the most reliable predictions for Airbnb rental pricing.

### 2. Business Insights (Best Hosts’ Practices)
- **Review Ratings Matter:** Higher guest ratings are strongly linked to increased demand and revenue. Properties in scenic suburbs (e.g., Pittwater, Mosman) often achieve higher review scores, suggesting that location quality plays a key role in long-term earnings.
- **Strategic Pricing Factors:** Average price is around $350 per night, with a range from budget ($17) to luxury ($2,617). Both guest capacity and bathrooms significantly influence price.
- **Interaction Effect:** The combination of more guest capacity and more bathrooms has the largest positive impact on price, outperforming either factor alone.
- **Recommendation for Hosts/Investors:** Improve both capacity (extra beds, reconfigured spaces) and bathroom facilities to maximize listing price and revenue. Invest in scenic or coastal properties to attract higher demand and long-term profitability.



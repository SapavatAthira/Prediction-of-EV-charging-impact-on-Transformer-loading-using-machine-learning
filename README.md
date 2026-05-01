# Prediction-of-EV-charging-impact-on-Transformer-loading-using-machine-learning


This project harnesses machine learning to anticipate how electric vehicle (EV) charging will affect transformer loading. By examining EV charging session data, the system estimates charging power and spots possible transformer overload dangers.

# Key Features:
- Data Processing: It tidies up and crafts features from EV charging session data.
- Predictive Models: It uses Linear Regression, Random Forest, and XGBoost.
- Load Forecasting: It predicts charging power (kW) for future sessions.
- Risk Detection: It sorts sessions that might cause transformer overload (over 50 kW).
- Visual Analytics: It offers thorough exploratory data analysis and performance visuals.

# Requirements:
1. text
2. pandas
3. numpy
4. matplotlib
5. seaborn
6. scikit-learn
7. xgboost
8. scipy

# Usage:
- Put your EV session data (acndata_sessions.json) in the spot it's supposed to go.
- Run the notebook to prepare the data, train the models, and get predictions.
- Look over the visual results to see how the models did and get some insights.

# Outputs:
- Model performance stats and comparison charts.
- Feature importance rankings.
- Residual analysis graphs.
- Demand forecasts by the hour.
- Transformer overload risk classifications.


# 🗽🚕 NYC Taxi Tipping Pattern Analysis
This project analyzes tipping behavior in NYC taxi rides using over 10 million trip records. We built predictive models to uncover what factors drive tipping and how these insights can be used to optimize services in the transportation industry.

Overview:

Explored and modeled tipping behavior in the New York City Yellow Taxi dataset using advanced feature engineering, regression analysis, and machine learning techniques. External data such as weather conditions and borough-level income were also integrated to improve prediction accuracy.

Objectives:

-Identify key factors influencing taxi tipping behavior.

-Engineer relevant features including tip ratio and socioeconomic indicators.

-Develop and compare predictive models using machine learning techniques.

-Provide actionable insights for optimizing revenue and customer satisfaction in urban transportation.



Project Structure:

-feature_engineering_and_EDA.ipynb     # Data cleaning, merging, and exploratory data analysis

-model_selection.ipynb                 # Feature selection and model building (Lasso, Linear Regression, Random Forest)


Methodology:

Data Sources: NYC Open Data (Yellow Taxi Trips), Borough Income Data, Weather Data


Feature Engineering:

-Tip Ratio (Tip / Fare)

-Average borough income

-Daily weather variables


Modeling Techniques:

-Linear Regression with and without Lasso feature selection

-Random Forest Regression (best accuracy: R² ≈ 0.57 on test set)


Key Results:

-Top predictors: payment_type, fare_amount, trip_duration, additional_charges, borough_income

-Random Forest achieved Test R² = 0.57, outperforming linear models

-Weather and demographic variables provided moderate predictive power


Literature Support:
The model and features were guided by findings from over a dozen peer-reviewed studies and large-scale analyses, including works on socioeconomics, weather, group behavior, and service economics.


Future Work:
-Incorporate deep learning models for more complex non-linear relationships

-Add geospatial analysis to explore spatial tipping patterns

-Deploy as a web-based analytics tool for taxi operators

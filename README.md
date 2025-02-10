# Price-Prediction

## Brief Description
Predicting the selling price given the characteristics of the cars.

## Dataset
* Tabular data. MS Excel file (csv format)
* 402007 rows of data (i.e., 402007 cars)

### Data Dictionary
| Column     | Description                          |
|------------|--------------------------------------|
| `public_reference`    | House price in USD.                  |
| `mileage`     | Square footage of the house.         |
| `reg_code` | Number of bedrooms.                  |
| `standard_colour` | City where the house is located.     |
| `standard_make` | City where the house is located.     |
| `standard_model` | City where the house is located.     |
| `vehicle_condition` | City where the house is located.     |
| `year_of_registration` | City where the house is located.     |
| `body_type` | City where the house is located.     |
| `crossover_car_and_van` | City where the house is located.     |
| `fuel_type` | City where the house is located.     |
| `price` | City where the house is located.     | 

## Description
* This project applies several machine learning algorithms to predict cars prices (tabular data of 402007 cars).
* In this project were implemented the respective stages sucha as data processing, feature engineering, model building, and evaluation.
* 
Various models including linear regression, random forest, and gradient boosting were developed and compared. A custom ensemble model was designed to differentiate between classical and non-classical cars, aiming to capture distinct pricing patterns within a single predictive framework. Tree-based models, particularly random forest and gradient boosting, outperformed linear models.
A key finding of this study is the superiority of SHAP (SHapley Additive exPlanations) values over Partial Dependence Plots (PDPs) for model interpretation. While PDPs offered insights, they relied on the unrealistic assumption of feature independence, often violated in real-world datasets. SHAP values provided more reliable and nuanced interpretations of feature importance and interactions, especially for correlated features like age and mileage.
This study contributes to the field by demonstrating the challenges in creating a unified model for diverse car categories, highlighting the importance of feature engineering, and emphasizing the value of SHAP analysis over PDPs for model interpretability in practical machine learning applications for automobile price prediction.This study applies advanced machine learning techniques to predict automobile prices using Autotrader data, with a particular focus on addressing the challenge of simultaneously predicting prices for both classical and non-classical cars. The research encompasses comprehensive data processing, feature engineering, model building, and evaluation. Various models including linear regression, random forest, and gradient boosting were developed and compared. A custom ensemble model was designed to differentiate between classical and non-classical cars, aiming to capture distinct pricing patterns within a single predictive framework. Tree-based models, particularly random forest and gradient boosting, outperformed linear models. A key finding of this study is the superiority of SHAP (SHapley Additive exPlanations) values over Partial Dependence Plots (PDPs) for model interpretation. While PDPs offered insights, they relied on the unrealistic assumption of feature independence, often violated in real-world datasets. SHAP values provided more reliable and nuanced interpretations of feature importance and interactions, especially for correlated features like age and mileage. This study contributes to the field by demonstrating the challenges in creating a unified model for diverse car categories, highlighting the importance of feature engineering, and emphasizing the value of SHAP analysis over PDPs for model interpretability in practical machine learning applications for automobile price prediction. 

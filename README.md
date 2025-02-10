# Price-Prediction

## Brief Description
Predicting the selling price given the characteristics of the cars.

## Dataset
* Tabular data. MS Excel file (csv format)
* 402005 rows of data (i.e., 402005 cars)
* The dataset shows twelve (12) columns, where eleven (11) were features and one (1) was the target variable.
* From  the  twelve  (12)  columns  shown,  (8)  columns  represent  physical attributes of the vehicle except for the subjective variable of "price", and the  systemic  features  (from  public  or  private  organizations) of "public_reference", "reg_code", and "year_of_registration"

### Data Dictionary
| Column     | Description                          |
|------------|--------------------------------------|
| `public_reference`    | reference code of the vehicle                 |
| `mileage`     | mileage of the vehicle         |
| `reg_code` | registration code of the vehicle                 |
| `standard_colour` | color of the vehicle      |
| `standard_make` | manufacturer of a vehicle, e.g. Tesla    |
| `standard_model` | model of vehicle, e.g. Corolla     |
| `vehicle_condition` | new or used     |
| `year_of_registration` | date the vehicle was first registered    |
| `body_type` | body type of the vehicle e.g. SUV     |
| `crossover_car_and_van` | true or fals    |
| `fuel_type` | The vehicle fuel type e.g. Diesel     |
| `price` | target variable (in £)     | 

## Description
* This project applies several machine learning algorithms to predict cars prices.
* In this project were implemented the respective stages sucha as data processing, feature engineering, model building, and model evaluation.
* Models implemented:
** including linear regression, random forest, and gradient boosting were developed and compared. A custom ensemble model was designed to differentiate between classical and non-classical cars, aiming to capture distinct pricing patterns within a single predictive framework. Tree-based models, particularly random forest and gradient boosting, outperformed linear models.
A key finding of this study is the superiority of SHAP (SHapley Additive exPlanations) values over Partial Dependence Plots (PDPs) for model interpretation. While PDPs offered insights, they relied on the unrealistic assumption of feature independence, often violated in real-world datasets. SHAP values provided more reliable and nuanced interpretations of feature importance and interactions, especially for correlated features like age and mileage.
This study contributes to the field by demonstrating the challenges in creating a unified model for diverse car categories, highlighting the importance of feature engineering, and emphasizing the value of SHAP analysis over PDPs for model interpretability in practical machine learning applications for automobile price prediction.This study applies advanced machine learning techniques to predict automobile prices using Autotrader data, with a particular focus on addressing the challenge of simultaneously predicting prices for both classical and non-classical cars. The research encompasses comprehensive data processing, feature engineering, model building, and evaluation. Various models including linear regression, random forest, and gradient boosting were developed and compared. A custom ensemble model was designed to differentiate between classical and non-classical cars, aiming to capture distinct pricing patterns within a single predictive framework. Tree-based models, particularly random forest and gradient boosting, outperformed linear models. A key finding of this study is the superiority of SHAP (SHapley Additive exPlanations) values over Partial Dependence Plots (PDPs) for model interpretation. While PDPs offered insights, they relied on the unrealistic assumption of feature independence, often violated in real-world datasets. SHAP values provided more reliable and nuanced interpretations of feature importance and interactions, especially for correlated features like age and mileage. This study contributes to the field by demonstrating the challenges in creating a unified model for diverse car categories, highlighting the importance of feature engineering, and emphasizing the value of SHAP analysis over PDPs for model interpretability in practical machine learning applications for automobile price prediction. 

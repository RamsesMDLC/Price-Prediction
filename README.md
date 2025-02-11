# Price-Prediction

## Brief Description
Predicting the selling price given the characteristics of the cars.

## Dataset
* Tabular data. MS Excel file (csv format).
* 402005 rows of data (i.e., 402005 cars).
* The dataset shows twelve (12) columns, where eleven (11) were features and one (1) was the target variable.
* From  the  twelve  (12)  columns  shown,  (8)  columns  represent  physical attributes of the vehicle except for the subjective variable of "price", and the  systemic  features  (from  public  or  private  organizations) of "public_reference", "reg_code", and "year_of_registration".

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
| `year_of_registration` | date the vehicle was registered    |
| `body_type` | body type of the vehicle e.g. SUV     |
| `crossover_car_and_van` | true or false    |
| `fuel_type` | The vehicle fuel type e.g. Diesel     |
| `price` | target variable (in £)     | 

## Description
* This project applies several machine learning algorithms to predict car prices.
  * Models implemented: linear regression, polynomial regression, random forest, boosted trees, and ensemble. 
* In this project, the respective pipelines were developed and implemented to execute data processing, feature engineering, model application, model evaluation, and model comparison.
* SHAP (SHapley Additive exPlanations) and Partial Dependence Plots (PDPs) were used for model interpretability.

![image](https://github.com/user-attachments/assets/fda3d91c-b523-447d-a353-ac19d0b6be60)


## Key Insights
* Random forest and boosted trees outperformed linear regression and polynomial regression, which is reasonable considering the distinct pricing patterns in the dataset.
* The results of this project demonstrate the relevance of using different machine learning models for the prediction of car prices (i.e., for specific price ranges, there are specific models with better performance). In other words, a single machine learning model is not able to predict with high accuracy the price of all the cars that are in the dataset.
* Feature engineering is extremely important to improve the performance of the models.

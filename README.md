# Deutsche Used Car Price

![ShowRoom](image/car_showroom.jpeg)


## Introduction

The objective of this project is to develop a machine learning model that accurately predicts the price of used cars based on various attributes, such as model, color, year, mileage, condition, and other relevant features.

## Dataset
The dataset contains the information about the used cars from one of Germany's largest car sales websites, AutoScout24. This scraped dataset contains a wide range of information about car offers, covering a cars manufactured from 1995 to 2023.

**Link:** https://www.kaggle.com/datasets/wspirat/germany-used-cars-dataset-2023


## Models

Used the XGBoost, LightGBM, and CatBoost Algorithm

## Model Evaluation 

Evaluate the models using RMSE and R² metrics.

## Outcome

| Model  | R² | RMSE  |
|---|---|---|
|  LightGBM | 0.912955  | 3314.699804  |
|  XGBoost |  0.916546 |  3245.617915 |
|  CatBoost | 0.917652  |  3224.034970 |

The CatBoost model achieved the best performance with an RMSE of 3224.03 and an R² of 0.917652. The model can be used to predict the price of used cars based on their attributes.

## Further Work
 
* Create a API to deploy the Model

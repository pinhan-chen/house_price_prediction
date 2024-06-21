# House Price Prediction

This project was finished in 2020 for the [Kaggle House Prediction Competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques). It was my first time using ensemble learning techniques to integrate GBDT such as XGBoost, LightGBM and CatBoost, which were the most popular models at that time. 

In the end, it achieved a RMSE of 0.1172, which ranked top 3% in the competition.

## Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Evaluation](#evaluation)
- [License](#license)

## Introduction
Accurately predicting house prices is crucial for various stakeholders, including buyers, sellers, and real estate agents. This project explores different machine learning models to predict house prices based on features such as the number of bedrooms, location, and lot size.
## Data
The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data). It includes various features that describe aspects of residential homes in Ames, Iowa.
## Installation
To run this project, you'll need to have Python 3.8 or higher installed. Follow the steps below to set up the environment:

1. Clone the repository:
```bash
    git clone https://github.com/pinhan-chen/house_price_prediction.git
    cd house_price_prediction
```
    
    
## Usage
To train and evaluate the models, run the Jupyter Notebook final_code.ipynb:
```bash
    jupyter notebook
```

Open and run all cells in final_code.ipynb.

## Models
The project includes the following models:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Ridge Regressor
- Lasso Regressor
- Elastic Net Regressor
- XGBoost
- LightGBM
- CatBoost

## Evaluation
The models are evaluated based on the Root Mean Squared Error (RMSE). The evaluation metrics are calculated on the test dataset to measure the performance of each model.


## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.




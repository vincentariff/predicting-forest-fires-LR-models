# Predicting Forest Fires Using Linear Regression Models

## Table of Contents

* [Introduction](https://github.com/vincentariff/predicting-forest-fires-LR-models#introduction)
* [Dataset](https://github.com/vincentariff/predicting-forest-fires-LR-models#dataset)
* [Requirements](https://github.com/vincentariff/predicting-forest-fires-LR-models#requirements)
* [Installation](https://github.com/vincentariff/predicting-forest-fires-LR-models#installation)
* [License](https://github.com/vincentariff/predicting-forest-fires-LR-models#license)

## Introduction

* IIn this project, we will predict the impact of forest fires in the northeast region of Portugal using linear regression.

* We log-transformed the target variable, handled missing data with K-Nearest Neighbors (KNN) imputation, identified outliers, standardized the dataset, and implemented multiple linear regression models. These included sequential feature selection (forward and backward), Ridge regression, and evaluation using K-Fold cross-validation.

*  Using linear regression to predict forest fire damage didn’t yield satisfactory results. The right-skewed distribution of the target variable, with many extreme values near zero, disrupts the linearity between the predictors and the target variable.

## Dataset

* The dataset [_Forest Fires_](https://archive.ics.uci.edu/dataset/162/forest+fires) is sourced from the UCI Machine Learning Repositor, with a slightly modified version tailored for our specific needs.
* The dataset can be found in `fires.csv` file.

## Requirements

* All libraries and dependencies are listed in the `requirements.txt` file.

## Installation

Clone the repository:
 ```
git clone https://github.com/vincentariff/predicting-forest-fires-LR-models.git
```

Install dependencies:
```
pip install -r requirements.txt
```

## License

* This project is licensed under the MIT License, detailed in the `LICENSE.txt` file.

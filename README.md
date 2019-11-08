# Time Series Forecasting using AI Modeling 
Regression models built based on information coefficient of Taiwan Top50 Tracker Fund for return prediction.

The contributing model consists of the following process:
 - data preprocessing
 - log return calculation with numpy
 - Ranked information coefficient calculation with pandas
 - kfold CV Model Selection with sklearn
 - lightgbm model hyperparameter optimization with BayesSearchCV
 - random forest, xgboost models
 - return evaluation (comparing alpha and beta ratios)

## Build status
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger) [![codecov](https://codecov.io/gh/yunglinchang/timeseries_forecasting/branch/master/graph/badge.svg)](https://codecov.io/gh/yunglinchang/timeseries_forecasting)
## Code style
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)

## Python Packages Used
 - pandas
 - matplotlib
 - datatable
 - numpy
 - warnings
 - os
 - sklearn
 - lightgbm
 - xgboost

## Credits
This is the final project of Big Data and Fintech Practices class in 2019 Spring semester.

## License
MIT © [Yung-Lin Chang](),[Chu]()
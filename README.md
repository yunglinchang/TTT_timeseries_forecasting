# Time Series Forecasting using AI Modeling 
This project aims to predict which ratio (alpha and beta ratios) performs better on Taiwan Top50 Tracker Fund (TTT). The regression models including LightGBM, Random Forest, and XGBoost are built based on the ranked information coefficient (Ranked IC) of the fund. **The results showed that, by solely using alpha ratios, the total stock return performance exceeded the ROI of the Taiwan Capitalization Weighted Stock Index (TAIEX) by 20%.**


## Build status
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger) [![codecov](https://codecov.io/gh/yunglinchang/timeseries_forecasting/branch/master/graph/badge.svg)](https://codecov.io/gh/yunglinchang/timeseries_forecasting)
## Code style
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)

## Data Science Pipeline
The contributing model consists of the following process:
 - data preprocessing
 - log return calculation with NumPy
 - Ranked information coefficient calculation with Pandas
 - kfold CV Model Selection with scikit-learn
 - LightGBM model hyperparameter optimization with BayesSearchCV
 - Random Forest and XGBoost models
 - return evaluation (comparing alpha and beta ratios)

Code files:
* RANK IC之 AI 模型建立與預測_V8.ipynb

## Python Packages Used
* LightGBM
* Matplotlib
* Pandas
* XGBoost
* datatable
* NumPy
* os
* scikit-learn
* warnings

## Credits
This is the final project of the **Big Data and Fintech Practices** course in 2019 Spring semester.

## License
MIT License

Copyright (c) [2019] [Yung-Lin Chang, Chian-Fang Chiu]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

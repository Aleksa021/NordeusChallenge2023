# Data Science Challenge Readme

## Overview
This repository contains the solution for the Data Science challenge, which involves predicting league ranks based on input data. The challenge uses two machine learning models, namely XGBoostRanker and CatBoostRanker, to make predictions on the test data.

## Files
1. **jobfair_train.csv**: This file contains the input training data for the machine learning models.

2. **jobfair_test.csv**: This file is the test dataset on which the trained models will make predictions. It contains the same features as the training data but lacks the corresponding league ranks, which are to be predicted.

3. **league_rank_predictions.csv**: This output file contains the predicted league ranks for the test data. The predictions are generated using the XGBoostRanker and CatBoostRanker models.

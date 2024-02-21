# Demand Forecasting with Time Series Data

## Overview

This notebook focuses on demand forecasting using time series data. The primary approach involves splitting the data into each month and training models using various techniques such as linear regression and decision tree regression. The notebook repeats this process six times, withholding a different month each time for testing, and then evaluates the performance by taking the mean of each model's predictions.

## Contents

1. [Introduction](#introduction)
2. [Data Preprocessing](#data-preprocessing)
   - [Time Series Split](#time-series-split)
3. [Model Training](#model-training)
   - [Linear Regression](#linear-regression)
   - [Decision Tree Regressor](#decision-tree-regressor)
4. [Evaluation](#evaluation)

## Introduction

Demand forecasting is a crucial aspect of business planning. This notebook addresses the task of predicting demand using time series data. The strategy involves splitting the data into monthly segments and training regression models to capture the underlying patterns. The notebook then evaluates the models' performance by calculating the mean of their predictions.

## Data Preprocessing

### Time Series Split

The notebook employs a time series split technique, where data is segmented by month. For each iteration, one month is held out for testing, and the model is trained on the remaining data. This process is repeated six times, covering each month.

## Model Training

### Linear Regression

Linear regression models are utilized for demand forecasting. These models aim to establish a linear relationship between the input features and the demand variable.

### Decision Tree Regressor

Decision tree regression is another technique employed in the notebook. Decision trees capture non-linear relationships in the data and can handle complex patterns.

## Evaluation

The performance of the models is evaluated by taking the mean of each model's predictions across the six iterations. This approach provides a consolidated measure of predictive accuracy.



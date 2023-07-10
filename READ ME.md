# King County House Sales Analysis

This project aims to analyze the KC House dataset to gain insights into the housing market. The dataset contains information about various features of houses in King County, USA, such as square footage, number of bedrooms, bathrooms, and the corresponding sale prices.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Results](#results)

- [Contributing](#contributing)


## Introduction

The project uses both simple and mutliple linear regression models in order to predict future based on certain factors.The projects maina agenda is to undersstand and analysis the sales data. This in order to help shareholders on how to advice current and new customers.The motivation of performing was brought about with my experince in my recent housing hunting

## Dataset

The dataset used was provided by King County House. The data had numerous outliers together with missing values and infinite numbers.

## Data Cleaning

The dataset cleaning was a bit hectic due to the large dataset used. Using inbuilt python functions the missing values and infinite values in each row were dropped. The outliers were removed by use of the interquantile range 


## Exploratory Data Analysis
Statiscal analysis suited more in this data this made it easilier to come up tangible conclusions.Linear regression was mainly used to try to predicate the house prices based on the following;
  
  
  .`sqft_living15` - The square footage of interior housing living space for the nearest 15 neighbors
  .`sqft_living` - Square footage of living space in the home
  .`sqft_above` - Square footage of house apart from basement


## Results

The target variable (price) has strong relationship with the independent variables which help the model to be able to predict future prices.The model can moderately predict the prices as noted by the adjusted R^2 ,VIF and tolerance.


## Contributing

The project can be found in the github repository where you can easily fork to test your own ideas (https://github.com/janju796/King-County-House-Sales).if you notice errors made in the project please notify me at njugunajames796@gmail.c0m




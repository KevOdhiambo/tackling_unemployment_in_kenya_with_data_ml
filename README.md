# Tackling Unemployment in Kenya: A Data-Driven Approach

## Project Overview

This project aims to analyze and address unemployment in Kenya using data-driven insights and machine learning techniques. By leveraging mock data that simulates various factors affecting unemployment, we explore patterns, train predictive models, and generate actionable recommendations.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Project Structure](#project-structure)
4. [Features](#features)
5. [Data Description](#data-description)
6. [Methodology](#methodology)
7. [Results and Insights](#results-and-insights)
8. [License](#license)

## Installation

To run this project, you need Python 3.7+ and the following libraries:

``` 
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

To run the analysis, execute the main script:
```
python unemployment_analysis.py

```
## project-structure

unemployment_analysis.py: Main script containing all functions and analysis
README.md: This file, providing project overview and instructions

## Features

Data generation for unemployment factors in Kenya
Exploratory Data Analysis (EDA) with visualizations
Machine Learning model (Random Forest) for predicting unemployment rates
Feature importance analysis
Partial Dependence Plot for top features
Insights and recommendations based on the analysis

## Data Description
The mock dataset includes the following features:

Age
Education years
Work experience
Skills score
Rural/Urban location
Gender
Industry sector
GDP growth
Unemployment rate (target variable)

## Methodology

Generate mock data
Perform Exploratory Data Analysis
Prepare data for machine learning (scaling, encoding)
Train a Random Forest Regressor
Analyze feature importance
Generate partial dependence plots
Derive insights and recommendations

## Results and Insights
The analysis provides insights into the most significant factors affecting unemployment in Kenya. Key findings and recommendations are generated based on the model's results and feature importance.
Contributing
Contributions to improve the analysis or extend the project are welcome. Please follow these steps:

## License
This project is open-source and available under the MIT License.
# Industrial-Copper-Modeling


## Overview

The copper industry deals with less complex data related to sales and pricing. However, this data often suffers from issues such as skewness and noise, which can affect the accuracy of manual predictions. Dealing with these challenges manually can be time-consuming and may not result in optimal pricing decisions. 

This project aims to address these issues by leveraging machine learning techniques for two primary purposes:
1. **Price Prediction**: A regression model to predict the selling price of copper.
2. **Lead Classification**: A classification model to predict the likelihood of leads converting into customers.

## Problem Statement

The copper industry faces the following challenges:
1. **Pricing Predictions**: Manual predictions can be inaccurate due to skewness and noisy data.
2. **Lead Classification**: Difficulty in capturing and classifying leads effectively.

### Objectives
- **Regression Model**: Utilize advanced techniques such as data normalization, feature scaling, and outlier detection to build a robust model for predicting copper prices.
- **Classification Model**: Build a lead classification system to evaluate and classify leads based on the likelihood of them becoming customers.

## Features

- **Price Prediction**: Predict the selling price of copper using a machine learning regression model.
- **Lead Classification**: Classify leads as 'Won' or 'Lost' using a machine learning classification model.

##  Models
    1. Regression Model
      Purpose: Predict the selling price of copper.
      Techniques Used: Data normalization, feature scaling, outlier detection.
      Algorithm: Random Forest Regression .
      
    2. Classification Model
      Purpose: Classify leads as 'Won' or 'Lost'.
      Techniques Used: Data normalization, feature scaling, handling class imbalance.
      Algorithm: RandomForestClassifier (or any other robust classification algorithm).

## Data

The dataset contains various features related to copper sales and leads. Important features include:
- `Item Date`
- `Quantity`
- `Country`
- `Item Type`
- `Thickness`
- `Product Reference`
- `Delivery Date`
- `Customer ID`
- `Status` (Used for classification: 'Won' and 'Lost')
- `Application`
- `Width`
- `Selling Price`

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/industrial-copper-modeling.git
    cd industrial-copper-modeling
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Run the Streamlit application:
```bash
streamlit run app.py



## Project structure

industrial-copper-modeling/
│
├── data/
│   └── (your dataset files)
│
├── models/
│   ├── regression_model.pkl
│   └── classification_model.pkl
│
├── app.py
├── requirements.txt
└── README.md



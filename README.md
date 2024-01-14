# Medical Insurance Premium Prediction

## Overview

This project aims to predict medical insurance premiums based on various patient attributes and health-related features. The prediction is performed using machine learning techniques to assist in determining accurate premium prices for insurance policies.

## Dataset

The dataset includes the following features:

- Age
- Diabetes
- Blood Pressure Problems
- Any Transplants
- Any Chronic Diseases
- Height
- Weight
- Known Allergies
- History of Cancer in Family
- Number of Major Surgeries
- Premium Price (Target Variable)

## Project Structure

The project is organized as follows:

- **Dataset Loading Data Exploration:** Loading the dataset and exploring the data to understand the trends.

- **Data Preprocessing:** Understanding and cleaning the dataset, handling missing values, and preparing the data for modeling.

- **Model Selection:** Choosing appropriate machine learning models for regression (e.g., Random Forest, Gradient Boosting) based on the nature of the problem and dataset.

- **Hyperparameter Tuning:** Fine-tuning model hyperparameters to improve predictive performance.

- **Evaluation:** Assessing model performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.


## Getting Started

Follow these steps to reproduce the results:

1. Clone the repository:
   ```bash
   git clone https://github.com/suvroneil11/Medical-Insurance.git
   cd Medical-Insurance
   ```
   
2. Install Dependencies
     ```bash
     pip install -r requirements.txt
     ```

## Results
- I found that while training different models, RandomForest and XGBoost had the best training performance out of all the other models having Mean Absolute error
  of 1012.13 and 1155.96 respectively, so I decided to perform hyperparameter tuning in order to improve upon the results.
- Finally on the test dataset after doing hyperparameter tuning, I got MAE of 1276.22 and 1801.39 for Random Forest and XGBoost Models respectively.
- A lower MAE and error rate of 5.25% and 7.40% respectively from the mean of the original Premium values, indicate better predictive performance.
- Therefore, the model which I will be choosing for future predictions will be Random Forest as it has a lower prediction error rate. 


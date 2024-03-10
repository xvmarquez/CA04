# CA4 - Ensemble Machine Learning Model for Income Prediction

## Introduction

This assignment explores several ensemble machine learning models with the aim of predicting income levels. Using demographic data from the U.S. Census Bureau, our goal is to classify individuals into one of two income categories: ">50K" or "<=50K". This includes data preparation, model building of Random Forest, AdaBoost, Gradient Boosting, and XGBoost. Along with performance evaluations, hyperparameter tuning, and analysis.

## Prerequisites

- Python 3.6 or higher
- Familiarity with pandas for data manipulation
- Familiarity with scikit-learn for implementing machine learning models

## Data Source

The dataset, obtained from the Census Bureau, includes the following:

- **GitHub Repository:** [Census Income Data](https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true)
- **Attributes (Columns):** 7
- **Instances (Rows):** 48,842
- **Target Classes:** 2 ('>50K', '<=50K'; labels: 1, 0)

## Installation and Setup

Follow these steps to set up your environment:

1. Clone or download this repository to your local system.
2. Ensure Python and pip are installed on your system.
3. Install the required packages:

    ```bash
    pip install pandas scikit-learn matplotlib numpy xgboost
    ```

## Project Tasks

- **Data Preparation:** Perform necessary cleaning and transformations for the modeling process. [This was carried over from CA03]
- **Ensemble Modeling:** Utilize ensemble methods such as Random Forest, AdaBoost, Gradient Boosting, and XGBoost to build predictive models.
- **Performance Evaluation:** Calculate and analyze accuracy and AUC for each model.
- **Hyperparameter Tuning:** Optimize the 'n_estimators' parameter among others for improved model performance.
- **Visualization:** Graphically represent model performance against varying hyperparameters to select the optimal model.

## Conclusion and Analysis

In the final section, we will present:

- A table synthesizing the performance metrics in order to compare of model performance based on accuracy and AUC.
- A discussion on the balance between model complexity and predictive performance.
- An evaluation of computational efficiency to identify the most practical model for both accuracy and real-world application.

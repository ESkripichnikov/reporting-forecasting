# Revenues Forecasting Project

This project focuses on forecasting companies' revenues using machine learning techniques.

## Data Visualization

Some data visualizations are presented [here](https://eskripichnikov.github.io/reporting-forecasting/), showcasing insightful graphs and charts related to the dataset.

## Main Results

The main results of all models are presented in the following table, showing the performance metrics for each model:

| Metrics                                | Baseline | Baseline + l2 | CatBoost | CB + Additional Features | CB + Features + optimal hyperparameters | CB + Features + Optuna | Stacking | 
|----------------------------------------|----------|---------------|----------|--------------------------|-----------------------------------------|------------------------|----------| 
| SMAPE CV, k=3                           | 44.6489  | 34.7193       | 51.0819  | 43.3633                  | 38.8362                                 | 39.3193                | -        | 
| SMAPE Test                              | 43.4163  | 34.9807       | 59.5176  | 49.6803                  | 41.2173                                 | 40.2823                | 35.8913  |


## Project Structure

The project is structured as follows:

- `data`: contains the dataset used for training and testing the models.
- `docs`: folder with HTML files for the [GitHub page](https://eskripichnikov.github.io/reporting-forecasting/), including detailed reports and visualizations.
- `images`: folder with images used in the exploratory data analysis (EDA) notebook.
- `preprocessing.ipynb`: notebook for data preprocessing from raw Excel files, preparing the data for modeling.
- `EDA.ipynb`: exploratory data analysis notebook, examining the dataset and gaining insights.
- `models.ipynb`: notebook for training and testing various machine learning models for revenue forecasting.

Feel free to explore each notebook and folder for more details on data processing, analysis, and modeling.

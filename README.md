# Data Project Template

<a target="_blank" href="https://datalumina.com/">
    <img src="https://img.shields.io/badge/Datalumina-Project%20Template-2856f7" alt="Datalumina Project" />
</a>

## XGBoost in Python for Beginners
YouTube Tutorial - https://www.youtube.com/watch?v=aLOQD66Sj0g&t=3s

This project demonstrates how to build and optimize an XGBoost model in Python, following the tutorial from the YouTube video linked above.

# Overview
XGBoost is a powerful gradient boosting algorithm widely used for supervised learning tasks. This project focuses on using XGBoost for classification, specifically predicting whether a customer will subscribe to a term deposit based on the bank marketing dataset.

# Key Concepts
Data Exploration and Preparation:

# Loading and cleaning the dataset
Handling categorical features with TargetEncoder
Splitting data into training and testing sets
XGBoost Model:

Building an XGBoost classifier
Utilizing scikit-learn pipelines for streamlined data processing and model fitting
Hyperparameter Tuning:

Employing scikit-optimize for efficient hyperparameter optimization
Using Bayesian optimization to find the best hyperparameter combination
Model Evaluation and Prediction:

Evaluating model performance using ROC AUC score
Making predictions on new data
Feature Importance:

Visualizing feature importance to understand the model's decision-making


## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── README.md          <- The top-level README for developers using this project
├── data
│   ├── external       <- Data from third party sources
│   ├── interim        <- Intermediate data that has been transformed
│   ├── processed      <- The final, canonical data sets for modeling
│   └── raw            <- The original, immutable data dump
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
└── src                         <- Source code for this project
    │
    ├── __init__.py             <- Makes src a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    │    
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    ├── plots.py                <- Code to create visualizations 
    │
    └── services                <- Service classes to connect with external platforms, tools, or APIs
        └── __init__.py 
```

--------

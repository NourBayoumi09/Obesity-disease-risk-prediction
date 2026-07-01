# Obesity Disease Risk Prediction using LightGBM

A machine learning project for predicting obesity levels based on demographic, lifestyle, and dietary habits. The model is built using LightGBM with a preprocessing pipeline and hyperparameter tuning to improve classification performance.

## Overview

The goal of this project is to classify individuals into different obesity categories using health and lifestyle-related features. The notebook covers the complete workflow from data exploration to model training and prediction.

## Dataset

The dataset includes features such as:

- Gender
- Age
- Height
- Weight
- Family history with overweight
- Frequent consumption of high-calorie food
- Vegetable consumption frequency
- Number of main meals
- Food consumption between meals
- Smoking habit
- Daily water intake
- Calorie monitoring
- Physical activity frequency
- Time spent using technology
- Alcohol consumption
- Mode of transportation

**Target variable:** `NObeyesdad` (Obesity level)

## Project Workflow

- Data loading and inspection
- Exploratory Data Analysis (EDA)
- Data preprocessing
  - Standardization of numerical features
  - One-hot encoding of categorical features
- Building a preprocessing pipeline with `ColumnTransformer`
- Training a `LightGBMClassifier`
- Hyperparameter tuning using `RandomizedSearchCV`
- Model evaluation
- Generating predictions for submission

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- LightGBM


## Running the Project

1. Clone the repository.

```bash
git clone https://github.com/NourBayoumi09/Obesity-disease-risk-prediction-using-Lightgbm.git
```

2. Install the required packages.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn lightgbm
```

3. Open the notebook and run all cells.

## Results

The final model uses LightGBM with optimized hyperparameters found through `RandomizedSearchCV`. Feature preprocessing and model training are combined into a single pipeline to ensure consistent transformations during training and inference.


---

# Airplane Customer Satisfaction Project

## Overview
This project aims to analyze and predict airplane customer satisfaction based on feedback and various factors such as flight experience, service quality, and in-flight amenities. We leverage machine learning techniques to understand the key drivers of customer satisfaction and build models to predict satisfaction levels.

## Project Structure
- **`data/`**: Contains raw data from airline customer feedback and processed datasets used for model training.
- **`notebooks/`**: Jupyter notebooks for initial data exploration and analysis.
- **`src/`**: 
  - `data_ingestion.py`: Script for loading and ingesting data.
  - `data_cleaning.py`: Data cleaning and preprocessing functions.
  - `feature_engineering.py`: Code for creating new features from the existing data.
  - `model_training.py`: Code to train machine learning models for predicting customer satisfaction.
  - `model_evaluation.py`: Script to evaluate model performance.
  - `utils.py`: Utility functions for common tasks.
- **`models/`**: Stores trained machine learning models.
- **`reports/`**: Generated reports, such as model evaluation and project summaries.
- **`docs/`**: Contains documentation like the project scope, technical details, and explanations.

## Goals
- Understand the main factors influencing airplane customer satisfaction.
- Build machine learning models to predict satisfaction levels based on these factors.
- Provide insights that airlines can use to improve customer experience.

## Tools and Technologies
- **Python**: For data processing and modeling.
- **Jupyter Notebooks**: For exploratory data analysis (EDA).
- **Machine Learning Libraries**: Scikit-learn, XGBoost, etc.
- **Git**: Version control.

## How to Run
1. Clone the repository.
2. Install dependencies from `requirements.txt`.
3. Run the scripts from the `src/` folder for data processing and model training.
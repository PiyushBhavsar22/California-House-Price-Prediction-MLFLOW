# California House Price Prediction with MLflow

This repository contains an end-to-end implementation of a **California House Price Prediction** model using machine learning and **MLflow** for experiment tracking and model management.

## Project Overview

The **California House Price Prediction** project aims to predict house prices based on the given dataset using machine learning techniques. Key highlights include:

- **Experiment Tracking**: Use of **MLflow** for tracking experiments, managing metrics, hyperparameters, and models.
- **Hyperparameter Optimization**: The project implements a **Random Forest** model with hyperparameter tuning to achieve the best results.

## Features

- **Data Preprocessing**: Handling missing values, scaling, and encoding features.
- **Model Training**: Training a **Random Forest** regression model with tuned hyperparameters.
- **Experiment Tracking**: Logging parameters, metrics, and models using **MLflow**.
- **Model Registry**: Storing the best model with metadata for version control.

## Installation

### Prerequisites

- Python 3.8
- Virtual environment tool (`venv`)

### Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/piyushbhavsar22/california-house-price-prediction-mlflow.git
   cd piyushbhavsar22-california-house-price-prediction-mlflow
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   mlflow ui
   ```


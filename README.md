# Application of AI Learning Models in Seismology

## Overview

Natural disasters, especially earthquakes, have devastating effects on human lives and infrastructure. Predicting earthquake magnitude and depth remains a critical challenge in seismology. Our project leverages machine learning and deep learning techniques to develop predictive models that can help mitigate the impacts of earthquakes by improving resource allocation and preventive measures.

This repository showcases our approach to earthquake prediction using advanced AI models, feature selection techniques, and a comprehensive dataset.

## Features

- **Dataset**: A rich seismic dataset from Kaggle, spanning from 1990 to 2023, with over 3 million records.
- **Models Used**:
  - Extreme Gradient Boosting (XGBoost)
  - Random Forest
  - Recurrent Neural Networks (LSTM, GRU)
  - K-Nearest Neighbors (KNN)
- **Optimization**: Metaheuristic optimization using Particle Swarm Optimization (PSO) to select the most relevant features.
- **Performance Metrics**:
  - R² Score
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)

## Dataset

The dataset consists of seismic events with attributes like:
- Date and time
- Geographical coordinates (latitude, longitude)
- Magnitude and depth
- Affected region and other seismic parameters

### Source

The dataset is publicly available on [Kaggle]([https://www.kaggle.com/](https://www.kaggle.com/datasets/alessandrolobello/the-ultimate-earthquake-dataset-from-1990-2023)). It has been processed to remove unnecessary features, handle missing values, and encode categorical variables.

## Methodology

1. **Data Preprocessing**:
   - Cleaning the dataset
   - Encoding categorical variables
   - Handling missing values
2. **Feature Selection**:
   - Using PSO for optimal feature selection
3. **Model Training**:
   - Training and testing various models
   - Hyperparameter tuning for optimal performance
4. **Performance Evaluation**:
   - Comparing models based on accuracy and error metrics

## Results

The GRU-based RNN demonstrated the best performance, achieving high accuracy and generalization ability. PSO significantly improved model performance by selecting relevant features.

| Model              | R² Score | MAE   | MSE   | RMSE  |
|--------------------|----------|-------|-------|-------|
| XGBoost            | 0.9949   | 0.0211| 0.0067| 0.0819|
| Random Forest      | 0.9956   | 0.0179| 0.0058| 0.0760|
| KNN                | 0.9949   | 0.0247| 0.0068| 0.0824|
| LSTM               | 0.9956   | 0.0238| 0.0058| 0.0761|
| GRU                | 0.9959   | 0.0206| 0.0054| 0.0737|

## Applications

- Earthquake Early Warning Systems
- Identification of high-risk zones
- Improved disaster management and planning
- Development of earthquake-resistant structures

## Future Work

- Incorporating additional data sources like satellite imagery and geological surveys.
- Refining models to improve real-time prediction and alert systems.
- Developing region-specific models for more localized predictions.


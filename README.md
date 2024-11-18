# HVAC System Optimization with GRU

This repository contains the code and resources for optimizing HVAC (Heating, Ventilation, and Air Conditioning) system parameters in smart city environments. The focus is on leveraging machine learning techniques, particularly GRU (Gated Recurrent Unit), to forecast energy consumption and improve energy efficiency. This is part of our Design of Smart cities course, as a graded project.

## Project Overview

- **Objective**: Forecasting HVAC parameters such as heating power and optimize energy consumption in large public buildings.
- **Dataset**: Time-series data including temperature, humidity, heating power, outside temperature, and wind speed.
- **Model Used**: GRU12, chosen for its efficiency and ability to handle sequential data with temporal dependencies.

## Methodology

1. Data Preprocessing: Includes normalization and formatting for sequential input.
2. Model Training:
   - GRU architecture with 50 units.
   - Optimized using Adam optimizer and Mean Squared Error loss function.
3. Evaluation:
   - Metrics: Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and accuracy.

## Results

| **Model** | **MSE** | **RMSE** | **Accuracy (%)** |
|-----------|---------|----------|------------------|
| GRU       | 0.025   | 0.158    | 98%              |
| LSTM      | 0.030   | 0.173    | 97%              |
| ARIMA     | 0.045   | 0.212    | 92%              |


## Contributors

 - Vaibhavi Jha, Lakshay Roodkee, Abhi Mandloi

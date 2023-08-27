# Weather Forecasting Model

Welcome to the Weather Forecasting Model project! This project involves the use of a Deep Network LSTM model to predict weather conditions, specifically focusing on temperature and humidity. The model is designed to provide accurate forecasts based on historical hourly data.

## Overview

In this project, we utilize a Long Short-Term Memory (LSTM) neural network to predict temperature and humidity levels. The dataset used for training the model comprises historical hourly weather data for Delhi, spanning from 2009 to 2020. The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/hiteshsoneji/historical-weather-data-for-indian-cities?select=delhi.csv).

## Features

- Deep Network LSTM Model: The predictive power of Long Short-Term Memory networks is harnessed to forecast temperature and humidity levels effectively.

- Two-Channel Input and Output: The model utilizes a two-channel input to make predictions for both temperature and humidity, providing comprehensive insights.

## Getting Started

1. Clone the Repository:

   ```bash
   git clone https://github.com/Manav321/Weather-Forecasting-Model.git
   cd Weather-Forecasting-Model
   ```

2. Dataset:

   Download the historical hourly weather data CSV file for Delhi from [Kaggle](https://www.kaggle.com/datasets/hiteshsoneji/historical-weather-data-for-indian-cities?select=delhi.csv) and place it in the appropriate location within the project.

3. Model Code:

   The core of the project lies in the MATLAB Live Script [WeatherForecasting.mlx](https://github.com/Manav321/Weather-Forecasting-Model/blob/main/WeatherForecasting.mlx). This script contains the code for building, training, and evaluating the LSTM model for weather forecasting.

## Usage

1. Open [WeatherForecasting.mlx](https://github.com/Manav321/Weather-Forecasting-Model/blob/main/WeatherForecasting.mlx) using MATLAB or any compatible MATLAB editor.

2. Follow the instructions and comments within the script to understand the various steps involved in preparing the data, constructing the LSTM model, training the model, and making predictions.

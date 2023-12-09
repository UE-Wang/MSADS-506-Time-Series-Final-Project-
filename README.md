# MSADS-506-Time-Series-Final-Project

#### Team 3: Logan Van Dine & UE Wang

# Airline Baggage Complaints Time Series Data Analysis

## Introduction

Consumer satisfaction in the airline industry is significantly impacted by baggage-related issues, including theft, loss, damages, and misrouting. These problems not only affect passenger experiences but also contribute to substantial dissatisfaction and added expenses for airlines. Understanding the patterns and trends in baggage complaints is pivotal for airlines to address these issues effectively.

## Problem Statement

The prevalence of baggage-related problems, such as loss, damages, and misrouting, poses a significant challenge for airlines. Identifying patterns in baggage complaints across United Airlines, American Eagle, and Hawaiian Airlines between 2004 and 2010 is crucial. This analysis aims to delve into the time series data to uncover trends, anticipate potential issues, and propose preventive measures to reduce baggage-related consumer dissatisfaction and associated costs.

## Data Source

The data, sourced from Kaggle Inc., includes operating statistics for the mentioned airlines. Key metrics encompass flight schedules, cancellations, enplaned passengers, and baggage complaints.

## Metrics:

Baggage: Total passenger complaints for baggage theft, loss, damage, or misrouting.
Scheduled: Total flights scheduled by the airline.
Cancelled: Total number of flights canceled by the airline.
Enplaned: Total passengers boarding the airline's planes.

## Link to Dataset:
https://www.kaggle.com/datasets/gabrielsantello/airline-baggage-complaints-time-series-dataset

## Project Structure

Part 1: Exploratory Data Analysis
Part 2: Data Preprocessing
Part 3: Forecasting Models

#### All Airlines

Simple Exponential Smoothing (SES) demonstrates lower RMSE but struggles with capturing seasonality. Holt-Winter’s Exponential Smoothing (HWIN) excels in handling seasonal patterns and offers better accuracy, making it preferable for forecasting tasks where seasonal representation is critical.

#### Hawaiian Airline

The neural network model shows lower ME and RMSE, suggesting superior performance, but it tends to overfit data. STL+ARIMA exhibits well-balanced performance across multiple metrics, especially in RMSE, MAE, MPE, and MAPE, making it a promising choice due to its accuracy and stability, without overfitting concerns.


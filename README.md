# MSADS-506-Time-Series-Final-Project-


# Airline Baggage Complaints Time Series Data Analysis

## Introduction

Airlines thrive on meeting consumer demands for fast and convenient travel. However, various inevitable factors, including weather, mechanical issues, and labor strikes, often disrupt flight schedules and impact consumer satisfaction. Baggage-related problems, such as loss, delays, and damages, further affect the overall consumer experience.

## Problem Statement
Identifying trends in flight delays, cancellations, and baggage complaints is crucial for airlines to proactively address customer dissatisfaction, reducing costly expenses and enhancing passenger satisfaction. This analysis aims to uncover patterns in airline operations between 2004 and 2010, focusing on United Airlines, American Eagle, and Hawaiian Airlines.

## Data Source

The data, sourced from Kaggle Inc., includes operating statistics for the mentioned airlines. Key metrics encompass flight schedules, cancellations, enplaned passengers, and baggage complaints.

## Metrics:

Baggage: Total passenger complaints for baggage theft, loss, damage, or misrouting.
Scheduled: Total flights scheduled by the airline.
Cancelled: Total number of flights canceled by the airline.
Enplaned: Total passengers boarding the airline's planes.

## Link to Dataset:
https://www.kaggle.com/datasets/gabrielsantello/airline-baggage-complaints-time-series-d ataset

##P roject Structure

Part 1: Exploratory Data Analysis
Part 2: Data Preprocessing
Part 3: Forecasting Models

#### All Airlines

Simple Exponential Smoothing (SES) demonstrates lower RMSE but struggles with capturing seasonality. Holt-Winter’s Exponential Smoothing (HWIN) excels in handling seasonal patterns and offers better accuracy, making it preferable for forecasting tasks where seasonal representation is critical.

#### Hawaiian Airline

The neural network model shows lower ME and RMSE, suggesting superior performance, but it tends to overfit data. STL+ARIMA exhibits well-balanced performance across multiple metrics, especially in RMSE, MAE, MPE, and MAPE, making it a promising choice due to its accuracy and stability, without overfitting concerns.


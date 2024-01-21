# Bike Sharing Analysis

## Introduction

Bike-sharing systems have revolutionized traditional bike rentals by automating the entire process of membership, rental, and return. With over 500 bike-sharing schemes globally, these systems play a crucial role in traffic, environmental, and health issues. The detailed data features recorded by these systems make them valuable for research, transforming them into virtual sensor networks capable of sensing city motion.

## Overview

This project aims to analyze bike-sharing data from the Capital Bikeshare system in Washington D.C., USA, between 2011 and 2012. The rental process is influenced by environmental and seasonal settings, such as weather conditions, precipitation, weekday, season, and hour of the day. The dataset, obtained from Kaggle and contributed by Capital Bikeshare, includes hourly and daily counts of rental bikes, along with corresponding weather and seasonal information.

## Data Description

The dataset comprises 17389 instances, featuring hourly and daily counts of rental bikes. Key variables include date, season, year, month, hour, holiday status, weekday, working day indicator, weather conditions, temperature, feeling temperature, humidity, windspeed, and counts of casual, registered, and total rental bikes.

## Design Methodology

Two datasets are available: `day.csv` and `hour.csv`. We chose `hour.csv` for further visualization due to its inclusion of the 'hr' variable. Categorical variables were encoded numerically and then back to string values for better understanding. For instance, seasons were represented as winter, spring, summer, and fall.

## Visualizations

- Area plot of Casual Vs Registered Across months and years
- Area plot of Distribution of the number of users across different levels of Temp and ATemp
- Bar Plot for the Number of Rental Bikes Vs DateDay
- Bar Plot for the number of Users on Working and Non-Working Days
- Boxplot of Casual Vs Registered across Seasons
- Bubble plot of Count of Users on the days of the week
- Dot plot of Casual Vs Registered Users across hours and years
- Heatmap of Registered Users across each day of the week and season
- Stacked Barplot of Distribution of Casual and Registered Users based on Seasons
- Stacked Barplot of Distribution of Casual and Registered Users based on Weather
- Line plot of the number of users across months and years
- Distribution of average number of users for different levels of Windspeed, Humidity, and Temperature
- Treemap for the number of users in the hour range

## Conclusion

The analysis reveals that external factors such as seasons and weather significantly impact the number of bikes rented. Insights gained include the seasonal demand for bikes and the usage patterns of registered users, particularly for commuting. Relationships between the number of users and humidity, temperature, and windspeed provide valuable information for bike lenders to meet demand effectively. Overall, the project suggests that making bikes more available could benefit both riders and lenders.

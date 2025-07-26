# Identifying-Air-Quality-Zones-in-India-A-Clustering-Approach
This project analyzes air quality data across India to identify distinct air quality zones using clustering. It covers data loading, preprocessing, and exploratory data analysis of key pollutants.

# Project Overview

Dataset

Features

Data Preprocessing

Exploratory Data Analysis (EDA)

Modelling

The project aims to identify air quality zones in India by analyzing pollutant concentrations (PM2.5, PM10, NO2, CO, SO2, OZONE, NH3) using a clustering approach. It involves data cleaning, preprocessing, and exploratory analysis to understand regional air quality patterns.

Dataset
A CSV dataset containing hourly measurements of various air pollutants from monitoring stations across India. Key columns include state, city, pollutant_id, and pollutant_avg.

Features
Analysis focuses on average, minimum, and maximum concentrations of: PM2.5, PM10, NO2, CO, SO2, OZONE, and NH3.

Data Preprocessing
Steps include dropping irrelevant columns (last_update, country), reshaping data to pivot pollutant types, and handling missing values by imputing with state-wise means and dropping remaining nulls.

Exploratory Data Analysis (EDA)
Visualizes pollutant distributions and patterns, such as comparing CO levels across cities and analyzing PM10 levels against safe limits.


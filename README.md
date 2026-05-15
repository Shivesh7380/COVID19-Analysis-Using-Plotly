
## Project Overview

This project focuses on analyzing and visualizing global COVID-19 data using Python and Plotly Express. The project helps understand worldwide pandemic trends including confirmed cases, deaths, recoveries, testing statistics, continent-wise spread, and country-specific analysis through interactive visualizations.

The project uses Exploratory Data Analysis (EDA) techniques and visual analytics to study the impact and spread of COVID-19 around the world.

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly Express
- Plotly Graph Objects
- WordCloud
- Google Colab

# Dataset Information

The project uses multiple COVID-19 datasets containing:

- Country/Region
- Continent
- Population
- Total Cases
- Total Deaths
- Total Recovered
- Active Cases
- Total Tests
- WHO Region
- Daily COVID Statistics
- Death Conditions and Causes

Dataset Format: CSV

# Project Workflow

1. Importing Required Libraries
2. Loading COVID-19 Datasets
3. Data Cleaning and Preprocessing
4. Exploratory Data Analysis (EDA)
5. Interactive Data Visualization
6. Choropleth Map Visualization
7. Country-Specific Analysis
8. Word Cloud Visualization
9. Business and Analytical Insights

# Data Cleaning

The following preprocessing steps were performed:

- Removed unnecessary columns with excessive null values
- Checked dataset information and data types
- Handled missing values
- Processed COVID statistics for visualization

# Visualizations Included

The project includes various interactive visualizations such as:

- Bar Charts
- Line Graphs
- Scatter Plots
- Bubble Charts
- Choropleth Maps
- Animated Visualizations
- Word Clouds

# Key Analysis Performed

## 1. Country-wise COVID Analysis

- Total confirmed cases
- Total deaths
- Total recoveries
- Total testing statistics

## 2. Continent-wise Visualization

- COVID spread comparison by continent
- Bubble chart analysis
- Log-scale visualizations

## 3. Country-Specific Analysis

Performed detailed COVID trend analysis for the United States including:

- Confirmed cases
- Death trends
- Recovery trends
- Daily new cases

## 4. Choropleth Map Visualization

Created animated world maps to visualize:

- Global confirmed cases
- Death trends
- Recovery trends
- Virus spread over time

## 5. Word Cloud Visualization

Visualized the leading medical conditions associated with COVID-19 deaths using WordCloud.

# Key Insights

- COVID-19 cases showed exponential global growth during 2020.
- Higher confirmed cases were associated with higher death counts.
- Testing rates varied significantly across countries.
- Recovery trends improved over time in several regions.
- Respiratory diseases were among the leading causes associated with COVID-19 deaths.

# Learning Outcomes

Through this project, I learned:

- Exploratory Data Analysis (EDA)
- Interactive Data Visualization
- Plotly Express Visualizations
- Choropleth Map Visualization
- Data Cleaning and Preprocessing
- COVID-19 Trend Analysis
- Word Cloud Generation
- Analytical Storytelling using Data


# Future Improvements

Future enhancements for this project may include:

- Machine Learning-based COVID prediction
- Forecasting future trends
- Dashboard creation using Power BI/Tableau
- Real-time COVID data integration
- Advanced statistical analysis

# Project Structure

├── COVID19_Analysis.ipynb
├── covid.csv
├── covid_grouped.csv
├── coviddeath.csv
├── README.md
└── images/

# Sample Visualizations

## Choropleth Map
![COVID Map](images/covid_map.png)

## Bubble Chart
![Bubble Chart](images/bubble_chart.png)

## Scatter Plot
![Scatter Plot](images/scatter_plot.png)

# Reference

This project was implemented for learning and educational purposes using publicly available COVID-19 datasets and visualization concepts inspired by GeeksforGeeks articles.

# Conclusion

This project demonstrates how Python and Plotly Express can be used to analyze and visualize real-world pandemic datasets through interactive charts, maps, and analytical visualizations.

The project highlights the importance of data visualization and exploratory analysis in understanding global trends and making data-driven observations.

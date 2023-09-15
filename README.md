# Data Analysis Report: Oktoberfest Data

## Table of Contents

- [Data Analysis Report: Festival Data](#data-analysis-report-festival-data)
  - [Introduction](#introduction)
  - [Installation](#installation)
  - [Clone](#clone)
- [Data Overview](#data-overview)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Trends Over Time](#trends-over-time)
  - [Correlation Heatmap](#correlation-heatmap)
  - [Comparative Analysis](#comparative-analysis)
  - [Duration vs. Guests](#duration-vs-guests)
  - [Yearly Trends](#yearly-trends)
  - [Average Metrics](#average-metrics)
  - [Comparative Bar Charts](#comparative-bar-charts)
  - [Histograms](#histograms)
- [Regression Analysis](#regression-analysis)
  - [Beer Price vs. Beer Consumption](#beer-price-vs-beer-consumption)
  - [Roast Chicken Price vs. Roast Chicken Consumption](#roast-chicken-price-vs-roast-chicken-consumption)
- [Cluster Analysis](#cluster-analysis)
- [Anomaly Detection](#anomaly-detection)
- [Hypothesis Testing](#hypothesis-testing)
- [Price Difference Analysis](#price-difference-analysis)
- [Conclusion](#conclusion)

## Introduction

This report presents the findings of our data analysis project focused on festival data. The dataset contains information about various aspects of festivals spanning multiple years, including beer prices, beer consumption, roast chicken prices, roast chicken consumption, and guest counts. The goal of this analysis is to explore trends, relationships, and insights within the dataset.

## Installation

## Clone

## Data Overview

The festival dataset consists of the following columns:

- `Year`: The year of the festival.
- `Duration`: The duration of the festival in days.
- `Guests Total`: The total number of guests attending the festival.
- `Guests Daily`: The number of guests attending the festival on a daily basis.
- `Beer Price`: The price of beer at the festival.
- `Beer Consumption`: The consumption of beer at the festival.
- `Roast Chicken Price`: The price of roast chicken at the festival.
- `Roast Chicken Consumption`: The consumption of roast chicken at the festival.

## Exploratory Data Analysis (EDA)

### Trends Over Time

I started by analyzing the trends of various festival metrics over time. The following observations were made:

- **Guests vs. Year**: The total number of guests attending the festival has generally increased over the years, with a few fluctuations.
- **Beer Price vs. Beer Consumption**: There appears to be a negative correlation between beer price and beer consumption, suggesting that as beer prices increase, beer consumption decreases.
- **Roast Chicken Price vs. Roast Chicken Consumption**: Similarly, roast chicken price and consumption exhibit a negative correlation.

### Correlation Heatmap

I created a correlation heatmap to visualize the relationships between different variables. The heatmap confirmed the observed negative correlations and highlighted strong positive correlations between certain variables.

### Comparative Analysis

I conducted a comparative analysis between beer and roast chicken metrics. Scatter plots were used to analyze the relationship between prices and consumption for both beer and roast chicken. Regression lines were added to visualize the trend.

### Duration vs. Guests

To analyze the impact of festival duration on the number of guests, I conducted a correlation analysis. It was observed that there is a mild positive correlation between festival duration and the total number of guests.

### Yearly Trends

Line plots were used to showcase how beer price, beer consumption, roast chicken price, and roast chicken consumption have changed over the years. This allowed us to identify trends and fluctuations in these metrics.

### Average Metrics

I calculated and plotted the average values for metrics such as beer price, beer consumption, roast chicken price, and roast chicken consumption over time. This provided a clearer picture of the central tendencies in these metrics.

### Comparative Bar Charts

Bar charts were created to compare metrics like beer consumption and roast chicken consumption side by side for each year. This helped visualize changes and variations between these metrics over time.

### Histograms

Histograms were generated to explore the distribution of variables such as `guests_total` and `guests_daily`. These histograms provided insights into the guest attendance patterns.

## Regression Analysis

### Beer Price vs. Beer Consumption

I conducted regression analysis to predict beer consumption based on beer price. The regression model showed a negative relationship between these variables, suggesting that higher beer prices result in lower consumption.

### Roast Chicken Price vs. Roast Chicken Consumption

Similar to the beer analysis, I performed regression analysis for roast chicken price and consumption. The results indicated a negative relationship, with higher prices leading to lower consumption.

## Cluster Analysis

I explored potential clusters or groups within the dataset using clustering algorithms. However, the analysis did not reveal distinct clusters, indicating that the data may not naturally form distinct groups.

## Anomaly Detection

I identified potential outliers or anomalies in the dataset. Anomalies may indicate unusual events or errors, and further investigation may be required to understand their causes.

## Hypothesis Testing

Hypothesis testing was conducted to investigate relationships between variables. The following hypotheses were tested:

- Hypothesis 1: There is a significant difference in total guests in 2001 compared to other years.
- Hypothesis 2: There is a significant difference in beer consumption before and after a certain year.

The results of these tests can be found in the respective sections of the report.

## Price Difference Analysis

I calculated and visualized the price difference between festival beer prices and consumer beer prices. This analysis allowed us to understand how festival prices compared to consumer prices over time.

## Conclusion

In conclusion, this data analysis project provided valuable insights into festival data. I observed trends, correlations, and conducted hypothesis testing to gain a better understanding of the dataset. Additionally, I explored the relationship between festival prices and consumer prices.

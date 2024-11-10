# Building a Multivariate Time Series Model

## Introduction
The goal of this project is to examine the variations in economic indicators, including gross national product (GNP) and inflation/deflation, over time. This examination will allow forecasting possible economic difficulties that could emerge in the near future.

This project will scope, analyze, prepare, plot data, and seek to explain the findings from the analysis.

Here are a couple of questions that this project seeks to answer:

- What economic challenges are anticipated?      
- What is the latest observation??
- What is the earliest observation?
- Is the general trend upward or downward?



### Scenario
In addition to your research on energy consumption in the United States, you are also conducting studies on U.S. economic conditions. Your objective is to analyze how economic indicators such as gross national product (GNP) and inflation/deflation fluctuate over time. This analysis will enable you to predict potential economic challenges that may arise in the near future.

You possess a time series dataset that includes multiple variables. A univariate algorithm, such as ARIMA, will not suffice for your needs. Instead, you will need to employ a multivariate algorithm like VAR to effectively forecast the various economic factors involved.

**Data Sources:**

- economics_data.csv
  

## Project Goals
In this initiative, the viewpoint will be that of an economics analyst. The analyst's objective is to analyze how economic indicators such as gross national product (GNP) and inflation/deflation fluctuate over time.  As a result, the primary goals will be to understand economic conditions particualaryly through the lense of various finacial features and their predicted future use and to uncover emerging trends. Several questions will be asked:

- What economic challenges are anticipated?      
- Is the general trend upward or downward?



#### Why use a multiivariate forecasting algorithm to predict future energy output?
Forecasting proves to be highly effective in generating numerical predictions from data that displays temporal patterns, which aligns well with the objectives of this project. Instead of focusing on a single variable, multiple metrics will be analyzed. The simplicity of a univariate model will not suffice in this case.


## Data
An anonymized dataset that can be used to train the machine-learning model has been found. It is a CSV file containing 123 financial records. 


## Conclusions



- **What economic challenges were anticipated**? 
    - gdfim is forecasted to significantly decline in the late 80s and the early 90s, but seems to start
recovering.
    - gdfce is forecasted to significantly decline
- **What is the latest observation**?
    - July 1989
- **What is the earliest observation**?
    - January 1959
- **Is the general trend upward or downward**?

  _Most forecasts show an increase, though some start to dip_.

    - rgnp is forecasted to fluctuate in the early 1990s, but ultimately start growing.
    - pgnp is forecasted to mostly grow, with one hiccup in the late 80s.
    - ulc is forecasted to fluctuate and appears to even out.
    - gdfco is forecasted to grow.
    - gdf is forecasted to mostly grow.
    - gdfim is forecasted to significantly decline in the late 80s and the early 90s, but seems to start recovering.
    - gdfcf is forecasted to take a slight dip in 1990s, but then start growing.
    - gdfce is forecasted to significantly decline.

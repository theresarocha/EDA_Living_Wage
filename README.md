# Exploratory Data Analysis

- Author: Theresa Rocha
- Programming language: Python

# Objective

Exploratory data analysis with some information about the population of the 100 largest cities in the United States according to the Census 2020.
This analysis has the intention to answer the following questions:

- Which city has the largest population?
- Which city has the smallest number of residents?
- Which city has the highest population density?
- Which city has the lowest population density?
- What is the average hourly minimum wage per one adult?
- What is the average hourly minimum wage per two adults wich just one is currently working?
- What is the average hourly minimum wage per two adults wich both are currently working?


# Data Source

- Dataset extracted from Kaggle: <https://www.kaggle.com/datasets/brandonconrady/living-wage-top-100-cities>
- US States Json from PublicaMundi: <https://github.com/PublicaMundi/MappingAPI/tree/master/data/geojson>

#Importing dataset

import pandas as pd

url = 'https://raw.githubusercontent.com/theresarocha/EDA_Living_Wage/main/livingwage%20(2).csv'
data = pd.read_csv(url)




## Data Analysis Nanodegree

---
## Project 1: Explore Weather Trends
#### Created by: Juanita Smith
#### Last date: 11 October 2022

---

## Project Overview
This project is completed as part of the 'Data Analyst' nanodegree with Udacity. 

The goal of the project is to analyze local and global temperature data and compare the temperature trends where you live to overall global temperature trends.

**This project requires the following steps:**

1. Extract data from a database using a SQL query
2. Calculate a moving average in a spreadsheet or pandas
3. Create a line chart in a spreadsheet or pandas


### Data

Data needed to be extracted from a SQL database supplied by Udacity, using SQL queries of choice.
It's part of the project deliverables to figure out the right SQL statement to download the data  

**There were three tables in the database:**
1. city_list - This contains a list of cities and countries in the database. Look through them in order to find the city nearest to you.
2. city_data - This contains the average temperatures for each city by year (ºC).
3. global_data - This contains the average global temperatures by year (ºC).

The final dataset constructed contains 3 fields:
1. year: (format YYYY) from 1750 to 2013
2. global_avg_temp: Global average temperature per year
3. uk_birmingham_avg_temp: United Kingdom Birmingham average temperature per year


### Decisions made

- **United Kingdom, Birmingham** was chosen as the local city closest to me
- **Pandas** were chosen to analyse the data instead of spreadsheets to strengthen python knowledge.

## Requirements
- Python 3 (Python 3.9 interpreter was used)
- Libraries needed:
    - pandas==1.4.4
    - numpy==1.21.5
    - matplotlib==3.5.2
    - jupyter notebook=1.0.0
    - nb_conda=2.2.1


## Installation

To clone the repository: 'https://github.com/JuanitaSmith/weather_patterns.git'


## Resources used:

pandas time series documentation


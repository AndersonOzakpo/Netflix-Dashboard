## Netflix Shows Analysis

### Table of Content

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Modelling and Analysis](#data-modelling-and-analysis)
- [Results or Findings](#results-or-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

  
### Project Overview

This analysis provides insights into Netflix shows since their inception. We are considering various aspects such as movies and TV shows, title type, director, cast, country of production, release year, rating, duration, genres (listed), and a brief description.

### Data Sources

Netflix Titles: The primary dataset used for this analysis is the "netflix_titles.csv" file containing detailed information about Netflix shows and movies.

### Tools Used

- Google Sheet - Data cleaning
  - [Try Google Sheet here](https://docs.google.com/spreadsheets/)
- Looker Studio - Data modeling, analysis & visualization
  - [Try Looker Studio here](https://lookerstudio.google.com/)
 
### Data Cleaning

The following tasks were performed:
1. Data loading and inspection
2. Handling missing values
3. Removing duplicate values
4. Properly formatting the data

### Exploratory Data Analysis

The EDA involved exploring the datasets to answer the following questions:
1. What are the overall shows for the period in view?
2. Is the volume of shows increasing or declining YoY?
3. What is the performance by type?
4. What rating has the highest volume?
5. What countries are the top shows coming from?
6. What genre has the highest shows?

### Data Modelling and Analysis

The following tasks were performed:
1. Definition and computation of derived metrics
2. Mapping relational datasets and tables

### Results or Findings
The analysis results are as follows:
1. The analysis shows that Netflix titles were flat from inception until 1996 where it maintained a steady rise seeing its peak in 2018.
2. So far, movies control over 69.6% of the total titles.
3. The United States dominated other movie industries. But drilling down by country, the South Korea and Spain industry has seen the biggest movements

### Recommendations
Based on the analysis, we recommend the following actions:
1. Increase the volume of shows from other industries for cultural inclusiveness
2. Get user preferences to better understand what industry has the highest consumer demand
3. Increase the volume of shows by South Korean and Spanish industry

### Limitations
There were not enough attribute and metrics in the dataset that defines consumer insights. Also, the where null values, considering this diagnostic analysis, the nulls won't impact the conclusions of the analysis.

### References
1. [Introduaction to Data Studio](https://analytics.google.com/analytics/academy/course/10/unit/1/lesson/3)


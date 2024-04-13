## Proyect description

With the aim of opening a small café in Los Angeles, we conducted a market study based on various open data sources of restaurants in the city.

## Tasks

1. Preprocess the data for analysis.
2. Data Analysis:
   - Investigate the proportions between types of establishments.
   - Characteristics of the establishments.
   - Number of seats for each type of restaurant.
   - The best commercial sectors in Los Angeles.
3. Conclusions.

## Data Description

Table rest_data:

- object_name — establishment name
- chain — establishment belonging to a chain (TRUE/FALSE)
- object_type — type of establishment
- address — address
- number — number of seats

## Table of Contents

1. Initialization:
   - Verification and Description
   - Data Loading
   - Preliminary Conclusions

2. Data Preprocessing:
   - Duplicate Checking
   - Missing Data Checking
   - Data Verification in object_type
   - Data Verification in number
   - Pre-analysis Conclusions

3. Data Analysis:
   - Question Formulation
   - Types of establishments
   - Establishments that are part of a chain
   - Number of seats and quantity of establishments
   - Los Angeles streets and quantity of establishments
   - Seat distribution in popular sectors

4. Conclusions and Recommendations

## Used libraries

- pandas
- numpy
- matplotlib
- seaborn
- plotly

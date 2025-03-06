# Baywheels System Analysis

## Project Overview
---
The FordGo Bike system dataset provides anonymized, timestamped data about the start- and end- station for a bike, the user type (subscriber or casual rider), as well as some customer-reported attributes like birth year and gender. This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
This notebook explores and documents the exploratory process of the FordGo Bike data.

## Data Sources
---
The primary source of Data used is fordgobike-tripdata.csv. This is an open source data that can be freely downloaded from Kaggle or any other open source data repository site.

## Analytical Tools
---
- Python
  1. For Data Cleaning
  2. For Analysis
  3. For Data Visualization
     
- Github for Portofolio Building

## Dataset
---
There are 183,412 distinct Go-ride listings with 20 features contained in the dataset. There are 8 numerical features but 2 (start_station_id, end_station_id) are categorical. There are 4 features with the latitude and longitudes of the start and end stations. The distance of the ride has been calculated. Also, the time of day and day of the week have been generated from the data.

## Data Cleaning and Preparations
---
In the initial phase of Data Cleaning, I performed the following actions;

- Data Type Normalization
- Statistical Operation
- Date-time Decomposition
- String Extraction
- Standardization of Data

## Exploratory Data Analysis
---
I performed an exploratory data analysis which aims to answer some key questions about this data such as;
- What time of the day do we have the most trips?
- What day of week do we have the most trips?
- When most trips take place?
- What's the average duration of trips taken?
- Does the above depend on if a user is a subscriber or customer?
- Which gender is more interested in bike trips?

## Summary of Findings
---
I was able discover different trends and uncover insights when i analysed FordGo Bike dataset. Most of the trips travelled for 500-800 seconds per ride with a frequency of more than 12,000. Most riders are male accounting for over 120,000 rides which is more than double the female and other gender combined. I also discovered that 89.2% of rides were from subscribers, while just 10.8% were customers paying daily.

Suprisingly, I discovered more than 20,000 bike trips were taken at 8am and 5pm on Tuesdays and Thursdays. The time of the day is when the weather is expected to be cooler and conducive for relaxation and riding.The majority of users are middle-aged adult with over 120,000 rides with both adolescents and old-aged adults following in distance with about 20,000 riders respectively. This is to be expected as the middle-aged adult tend to be more adventurous. From my analysis, I was able to note that long distant rides were rarely taken. Most of the rides are of short distances with short durations. Which lies in the range of under 30000 secs and 9 Kms. Also, most of the trips were taken by Middle-aged Adult(25 - 44yrs) which was on Thurdays and Tuesdays. Seniors(65+ yrs) took the least trips in all days of the week.

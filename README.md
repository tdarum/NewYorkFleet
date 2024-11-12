## Background

The New York City Taxi and Limousine Commission (TLC) regulates one of the largest, most active transportation systems in the world. With thousands of yellow cabs, green taxis, and for-hire vehicles crisscrossing the city daily, there are hundreds of millions of passenger trips annually, each creating a digital record of trip duration and distance, fare, and payment type. Aggregated data published by the NYC TLC illustrates salient features of transportation trends, economic activities, and mobility in city areas.

New York City is a global business hub, and it attracts many tourists too. Not only for the locals but also for the visiting tourists and traveling employees, taxi services need to be prompt. But at a time when the yellow cabs are getting tough competition from ride-sharing services and considering the task of navigating through the traffic of a heavily populated metropolis, efficiency and revenue optimization in conventional taxi services have gained paramount importance for both the policymakers and taxi operators.


##  Project Steps
The steps applied in this project will include but are not limited to these highlighted below.

### 1. Data Preprocessing and Cleaning
        - Handle missing values 
        - Convert date-time fields into an appropriate format and then extract relevant features from the date: hour, weekday, month.
        - Handle outliers in trip_distance and fare_amount-for instance, extremely high values for fare_amount.
        - Map location IDs to known NYC boroughs/zones for better insights.
### 2. Exploratory Data Analysis
        - Find peak hours, days of the week, and seasonal trends.
        - Map hot zones for pickups and drop-offs based on PULocationID and DOLocationID.
        - Look at fare vs. trip distance based on Rate Codes.
        - Check different usage patterns among different payment methods.
### 3. Add Column
        New features to be created are as follows:
        - trip duration : Time difference between dropoff and pickup.
        - Trip Speed: The trip distance divided by the trip time .
        - Rush Hour: Provides an indicator flag on whether it is rush hours.
### 4. Statistical Approach
### 5. Data Visualization

## Project Use Case
This analysis, therefore, attempts to take an approach concerned with maximizing the number of trips by taxis within New York City, which will translate into maximum revenue amongst the drivers and operators. The focus of this project, through the analysis of TLC Trip Record data, is thus to:

- Analyze the pattern and determinants of the number of trips. 
- Understand the relationship between payment types and fare amounts with trip counts and revenues.
- Remove those data inconsistencies, such as negative fare values, which may interfere with appropriate data analysis.
- Give actionable recommendations to drivers and operators on how to maximize their trip counts and revenues with insights such as the best operating hours or hotspots of high demand.



## Directory : 
- Capstone2Theresia-NYTaxi-Location.ipynb : data preparation code
- NYC TLC Trip Record.csv : Raw data that need to be cleaned
- NYC_Trip_cleaned_Location.xlsx : cleaned data
- Capstone2Theresia-NYTaxi Visualization.ipynb : data visualization file

## Tableau link 
- https://public.tableau.com/app/profile/theresia.diah/viz/NYCTaxi_17307281520960/MainTaxiDashboard?publish=yes



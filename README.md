# BigDataAnalytics
Coursework &amp; Projects under Prof Mohammad Soltanieh-Ha for the coursework Boston University IS 843 - Big Data Analytics for Business


## Introduction


**Problem definition**:

   After Uber and other taxi platforms took over the taxi market, it has left traditional taxi services quite vulnerable. Although these companies have looked into online platforms, they have long lost their original market shares. Therefore, this projects aims to focus on tradition taxi services' data and analyze trends and patterns to determine potential opportunities in aiding traditional taxi service companies.
    
**a.Motivation**

   In order to better provide aid to taxi service companies, the taxi trip dataset will help us gain insights on trends in the taxi industry. Moreover, these insights can be developed into business decisions relating to pricing, operation and marketing.
    Taxi services serve as a crucial means of transportation in urban regions, and examining taxi trip data with city crime data,  can offer valuable insights for enhancing the quality, safety and effectiveness of these services.

**b.Objective**

Pricing:  This aspect will primarily come from an analysis on fare distributions and its relations to other variables like location and time.  This can be used as a source for price optimization.

Operation: By analyzing the distribution of trip durations, outliers and anomalies can be found and discussed. Thus providing reasons and evidence for allocation.

Marketing: A full look at the data will help detect trends like popularity of areas and patterns like time of day demands. These can come in useful for a tailored service to the market.



**c.Data description**

   Our first dataset comprises taxi trips recorded by the City of Chicago's regulatory agency from 2013 to the current date, totaling 206,021,251 entries. This dataset has 22 columns, including unique taxi id, trip duration in seconds, distance in miles, pickup and dropoff community areas, fare, tips, tolls, extras, total cost of the trip, payment method, company, pickup and dropoff location, and start and end times of each trip.

Main Data sourced from CityOfChicago - BigQuery Public Datasets. See Main Data sourced from CityOfChicago - BigQuery Public Datasets.  
[chicago_taxi_trips](https://console.cloud.google.com/bigquery?p=bigquery-public-data&d=chicago_taxi_trips&page=dataset).
[chicago_crime](https://console.cloud.google.com/bigquery?p=bigquery-public-data&d=chicago_crime&page=dataset)



Taxi Data Set Website Link  https://data.cityofchicago.org/

Taxi Data sourced from https://data.cityofchicago.org/Transportation/Taxi-Trips/wrvz-psew

Crime Data sourced from https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2

*******






Project title : Chicago Taxi Ride Analysis
Problem definition :
To analyse taxi ride data in Chicago to identify patterns, trends, and factors that contribute to taxi rides. Also along with crime dataset, as both of the datasets contain  longitude and latitude, to investigate, eg. if certain area with higher crime rate will cause extra fee or how area with higher crime rate will impact the taxi service.
Data source :
 https://data.cityofchicago.org/Transportation/Taxi-Trips/wrvz-psew
 BigQuery Google Open Dataset - bigquery-public-data.chicago_taxi_trips.taxi_trips.
 BigQuery Google Open Dataset - bigquery-public-data.chicago_crime.crime
Motivation :
Taxi services serve as a crucial means of transportation in urban regions, and examining taxi trip data with city crime data,  can offer valuable insights for enhancing the quality, safety and effectiveness of these services.



# Human Activity Recognition

This repository contains the codes for an academic project I did at Purdue from Nov to Dec'2021.

## Problem
I am performing analytics to solve various business problems for the public bike share system Metro Bike in Austin, Texas. I have access to the bike-rental data in Austin through this [link](https://data.austintexas.gov/Transportation-and-Mobility/Austin-MetroBike-Trips/tyfh-5r8s). I will use concepts from graph theory, linear optimisation, and machine learning to solve the following problems.
-	Travelling Salesman Problem
-	Predicting trip duration
-	Clustering kiosks
-	Optimizing which kiosks to close
-	Minimum vertex cover

## About the data

The dataset that I imported had 130943 rows and 20 columns (after initial cleaning and merging multiple tables into one). A short description of the columns follows:
1.	Trip_ID – Unique code for each customer interaction with the business
2.	Membership_Type – There are 30 unique categories of customer who rented a bike including 7-Day Membership, Annual Membership, 24-hour Kiosk, etc. 
3.	Bicycle_ID – Unique code to identify the bike rented from 375 unique options all over
4.	Checkout_Date – Date when bike was rented
5.	Month – Month from the Checkout Date; 1-12
6.	TempAvgF – Average temperature of the city in F; 29-92F
7.	DewPointAvgF – Average Dew Point of the city in F; 8-74F
8.	HumidityAvgPercent – Average percentage of humidity in the air in the city; 27-97%
9.	VisibilityAvgMiles – Miles visible to the naked eye, measurement of fog; 2-10miles
10.	WindAvgMPH – Average speed of wind on that day; 1-11MPH
11.	PrecipitationSumInches -  Inches of rain or snow or hail on that day; 0-10inches
12.	Checkout_Kiosk_ID – Unique ID for the kiosk from where the bike was rented
13.	Checkout_Kiosk – Name of the Kiosk from where the bike was rented; 44 unique kiosks
14.	Checkout_Kiosk_latitude – Latitude of Checkout Kiosk
15.	Checkout_Kiosk_longitude – Longitude of Checkout Kiosk
16.	Return_Kiosk_ID – Unique ID for the kiosk to where the bike was returned
17.	Return_Kiosk – Name of the Kiosk to where the bike was returned; 44 unique kiosks
18.	Return_Kiosk_latitude – Latitude of Return Kiosk
19.	Return_Kiosk_longitude – Longitude of Return Kiosk
20.	Trip_Duration_Minutes – Time in minutes for when the bike was rented by the customer; 2mins – 5days

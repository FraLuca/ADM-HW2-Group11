# ADM-HW2-Group11
Homework 2 for ADM exam of DATA SCIENCE. Made by group 11

## Analysis of Taxis in NYC
In this homework we perform an analysis of NYC's taxis. In particular we answer to some specific *Research Question* about mobility in the different boroughs, months, time slots, trips last, and the payment way. Then we perform 2 analysis:

  - We use a Chi-squared test to see whether the method of payment is correlated to the borough.
  - We compute Pearson coefficient to see if the distance has a linear correlation with the duration of the trip on average.
  
At the end we answer to 2 *Core Reasearch Question*:

  - We see if the distributions of the Fare for each borough are statistically significant. And we do the same thing considering the Fare over the trip last to mitigate the traffic's effect.
  - We visualize on NYC map what is the frequency of the zones where the Taxi pick up and drop off the users.
 
********

### Download and Sample the Data
For this purpose we use the open data of Taxi's trips in NYC. In order to answer to the RQs and the CRQs we take into account the data related to for [Yellow CAB](http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml) in the year 2018.
There are approximately 8 million of data for each month considered. The huge number doesn't allows to use all the data so we take a random sample of the size of a million for each month.

********

## Script Description

> __`NAME.ipynb`__ 

This script is divided in this way:
- First we download and sample the data, then we remove all the strange data and those that seemed us wrong.
- Then we answer to all 5 Research Questions explaining the results through plots.
- Finally we make all the Core Research Questions.

A detailed description is provided in the file. 

## Visualization Problem

If you can't see some plot or map please try to see at this link: 

http://nbviewer.jupyter.org/github/Scarallallau/ADM-HW2-Group11/blob/master/Homework%202%20-%20Group%2011.ipynb


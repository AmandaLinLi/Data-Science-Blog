# Data-Science-Blog
Udacity Project1

# Overview

This project for the project 1 of Udacity Data Science Nanodegree program

# Libraries used

- Numpy
- pandas
- matplotlib
- sklearn
- seaborn
- math

# Database Used

COVID-19 Dataset:Number of Confirmed, Death and Recovered cases every day across the globe

# Motivations for the project:

## Primary motivation: 

- 1.  To demonstrate the top 10 countries with the greatest number of total confirmed cases and deaths of Covid-19
- 2.  To show and compare total confirmed vs. confirmed/million people, and total deaths vs. deaths/million people of Covid-19 in each WHO region
- 3.  To visualize deaths/100 cases and recovered/100 cases of Covid-19 among countries in each WHO regions

## Secondary Motivation
- Using machine learing (linear regression) method to show how some factors of interests contribute to death/100 cases 

# Files in the repository

README.md

udacity-project1.ipynb

# Summary of the results of the analysis

## Results of data visualization

- 1 country of Africa (South Africa), 5 countries of Americas (Chile, Peru, Mexico, Brazil, and US), 1 country of Eastern Mediterranean (Iran), 2 countries of Europe (United Kingdom, Russia), and 1 South-East Asia country (India) are among the top 10 countries who have the greatest number of total confirmed cases, 

- As for deaths of Covid-19, 4 countries of Americas (Peru, Mexico, Brazil and US), 1 country of Eastern Mediterranean (Iran), 4 countries of Europe (France, Spain, Italy, United Kingdom), and 1 South-East Asia country (India) are ranked top 10

- Americas have largest number of confirmed cases, confirm cases/ 1M people, deaths, deaths/ 1M people, followed by Europe among all WHO regions; western Pacific area has the least of all four metrics.  And, although total confirmed cases and deaths in South-East Asia seems high, the number per 1M people is relatively small. 

- Americas have relatived low recovery rate compared with their high death rate, while Europe have both high death rate and high recovery rate among the WHO regions

## Results of linear model analysis

  **Variables   Coefficients**
  
    Confirmed -0.000004
  
	Deaths	0.000411
  
	Recovered	-0.000005
  
	Active	-0.000010
  
	New cases	0.000400
  
	New deaths	-0.007451
  
	New recovered	-0.000262
	
	Recovered / 100 Cases	-0.006877
	
	Deaths / 100 Recovered	0.002012
	
	Confirmed last week	-0.000005
	
	1 week change	0.000015
	
	1 week % increase	-0.012441
	
	Americas	0.086453
	
	Eastern Mediterranean	2.046534
	
	Europe	0.739412
	
	South-East Asia	-0.852902
	
	Western Pacific	-0.94440



# Acknowledgements

Thanks Udacity for designing the project, and I also appreciate the database collected by Devakumar kp from https://github.com/CSSEGISandData/COVID-19 and
https://www.worldometers.info/

# Phase 2 Project


![insideimg.jpg](./insideimg.jpg)


## Project Overview

For this project, you will use regression modeling to analyze house sales in a northwestern county.

### The Data

OBTAIN - Data has been sourced from kc_house_data.csv.

This project contains the King County House Sales dataset, which is found in kc_house_data.csv of the data folder in this repo. The description of the column names can be found in column_names.md in the same folder. As with most real world data sets, the column names are not perfectly described, so we have determined and described the data columns below.

Features Ommited:

date
view
sqft_above
sqft_basement
yr_renovated
zipcode
lat
long
sqft_living15
sqft_lot15

Features Included:

price Purchase price
bedrooms How many beddrooms
bathrooms How many bathrooms
sqft_living How many square feet is the living area
sqft_lot How many square feet is the lot
floors How many floors
condition Condition (poor, good, excellent)
grade Indicating Grade / level
yr_built Year house was built
zipcode The zip code in the area

### Business Problem

King County Realty is a newly established local business in Northwestern America. They are seeking some information regarding what attracts local buyers in this area to purchase new homes. We wiill inspect the data set to determine what relationships and connections buyers have to purchasing a home and help King County Realty market their new business to suit.

A linear regression model will be used to understand the connections to the business problem usingthe OSMIN Model a our Data Science Process.

## Deliverables Attached are:

* A **GitHub repository**
* A **Jupyter Notebook**
* A **non-technical presentation**

OBTAIN - Data has been sourced from kc_house_data.csv.During this time we reviewed the business problem to determine that we had enough data to properly address the question and formulate a null and alternate hypothesis. 

SCRUB - The following methods were utilised to clean or "scrub" the data: Removed duplicates, drop unnecessary columns, removed null values, created lambda functions to remove exponential values, 
declared variables, set up column data to suit the business problem that made the most logical sense according to the business problem, and created data frames. Important steps such as identifying and removing null values, dealing with outliers, 
normalizing data, and careful selection was managed during this process. Obtaining the descriptive statistics was also imperative at this point. *Normalizing the data was performed here aswell, however is depicted after some exploratory analysis. 

EXPLORE - Exploratory Statistical analysis used was: KDE - Kernal Density Estimate was used to obtain PMF - Probability Mass Function, z- Test conducted, P Value derived, R squared Value via OLS was reviewed and in alignment within normal range of 0.493, Mean Standard Error, 


MODEL - Normalized the data as a best practice where it can be queried and manipulated, Created a dummy test set via 80/30 model - (17271 4318 17271 4318), Undertook a Y-Hat test to determine the best line of fit, 

INTERPRET - 


#3 important parameter estimates or statistics.

 #your notebook and presentation should discuss at least two features that have strong relationships with housing prices.
 
#after you finish refining your models, you should provide 1-3 paragraphs discussing your final model



## Summary

This project will give you a valuable opportunity to develop your data science skills using real-world data. The end-of-phase projects are a critical part of the program because they give you a chance to bring together all the skills you've learned, apply them to realistic projects for a business stakeholder, practice communication skills, and get feedback to help you improve. You've got this!

## For More Information 

Please review our full analysis in the Jupyter Notebook[Jupyter Notebook] (../PhasePro2_10.ipynb) or our [presentation](./presentation.pdf).

For more information contact **Carla Kirby, ra_carlajoy@yahoo.com** 
  

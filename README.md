# Phase 2 Project

![insideimg.png](./images/insideimg.png)

## Project Overview

For this project, you will use regression modeling to analyze house sales in a northwestern county.

## Business Problem
______________________________________________________________________________________________________________________________________________________________________

King County Realty is a newly established local business in Northwestern America. They are seeking some information regarding what attracts local buyers in this area to purchase new homes. We wiill inspect the data set to determine what relationships and connections buyers have to purchasing a home and help King County Realty market their new business to suit.

A linear regression model will be used to understand the connections to the business problem usingthe OSMIN Model a our Data Science Process.

### The Data
______________________________________________________________________________________________________________________________________________________________________

**OBTAIN**  
Data has been sourced from kc_house_data.csv.

This project contains the King County House Sales dataset, which is found in kc_house_data.csv of the data folder in this repo. The description of the column names can be found in column_names.md in the same folder. 

**SCRUB**
As with most real world data sets, the column names are not perfectly described, so we have determined and described the data columns below.

Features Ommited: Date, view, sqft_above, sqft_basement, yr_renovated, zipcode, lat, long, sqft_living15, sqft_lot15. 

Features Included: Price, bedrooms, bathrooms, sqft_living, sqft_lot, floors, condition, grade, yr_built, zipcode. 

The following methods were utilised to clean or "scrub" the data: Removed duplicates, drop unnecessary columns, removed null values, created lambda functions to remove exponential values, declared variables, dealt with outliers, set up column data to suit the business problem that made the most logical sense according to the business problem, and created data frames. Normalizing data and careful reviewed the data to purposefully address the buisness problem in a logical way. Descriptive statistics were also imperative at this point. *Normalizing the data was performed here aswell, however is depicted after some exploratory analysis. 

**EXPLORE - Exploratory Statistical analysis used was: KDE - Kernal Density Estimate was used to obtain PMF - Probability Mass Function, z- Test conducted, P Value derived, R squared Value via OLS was reviewed and in alignment within normal range of 0.493 and Mean Standard Error - MSE. K folds and cross vallidation to confirm findings.

**MODEL - Scatter Plots, histograms, linear regression best line of fit using Pandas, Numpy and Matplotlib, mapped residuals to confirm alternate hypothesis. 

**INTERPRET - 
(2) Two features that have strong relationships with housing prices - 

1. Sqft_living had the strongest linearity compared to sqft_lot which would be a resaonably strong connection to house sales in teh area. For example, the larger the lot the higher the price - however this was incorrect, the larger the sqft_living area was directly correlated with the inccreased house sales price. 

2. Final predicted date based on the dataset determined that the sqft_living, bathrooms and sqft_living, grade both leveled at .076 with strong connections to sale price - however bathrooms were not reviewed in this analysis as grade held a stronger inital correlation value of 67%.


#3 important parameter estimates or statistics.
1. There were 571 outliers in sqft_living.
2. 

 
#after you finish refining your models, you should provide 1-3 paragraphs discussing your final model


## Deliverables Attached are:

* A **GitHub repository**
* A **Jupyter Notebook**
* A **non-technical presentation**

## Summary
______________________________________________________________________________________________________________________________________________________________________

This project will give you a valuable opportunity to develop your data science skills using real-world data. The end-of-phase projects are a critical part of the program because they give you a chance to bring together all the skills you've learned, apply them to realistic projects for a business stakeholder, practice communication skills, and get feedback to help you improve. You've got this!

## For More Information 
______________________________________________________________________________________________________________________________________________________________________

Please review our full analysis in the Jupyter Notebook[Jupyter Notebook] (../PhasePro2_10.ipynb) or our [presentation](./presentation.pdf).

For more information contact **Carla Kirby, ra_carlajoy@yahoo.com** 
  

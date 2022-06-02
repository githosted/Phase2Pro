
# Phase 2 Project

![interiorhouse.png](./img/interiorhouse.png)

## Project Overview
___________________________________________________________________________________________________________________________________________

For this project, you will use regression modeling to analyze house sales in a northwestern county.

## Business Problem
___________________________________________________________________________________________________________________________________________

King County Realty is a newly established local business in Northwestern America. They are seeking some information regarding what attracts local buyers in this area to purchase new homes. We will inspect the data set to determine what relationships and connections buyers have to purchasing a home and help King County Realty market their new business to suit.

A linear regression model will be used to understand the connections to the business problem usingthe OSMIN Model a our Data Science Process.

## The Data

**OBTAIN** 

This project contains the King County House Sales dataset, which is found in kc_house_data.csv of the data folder in this repo. The description of the column names can be found in column_names.md in the same folder. If we were to expand the regional database or have more rows of data over time, we could enlarge the model and have more information to work with, creating a stronger prediction with more concrete evidence based details to present to King County. See https://finance.zacks.com/property-size-increase-home-value-9809.html to validate the strength of the lot theoretical versus the grade of a home to ensure that the real world approach to this research and data project has been approached validly. 

**SCRUB**

The following methods were utilised to clean or "scrub" the data: Removed duplicates, drop unnecessary columns, removed null values, created lambda functions to remove exponential values, declared variables, dealt with outliers, set up column data to suit the business problem that made the most logical sense according to the business problem, and created data frames. Normalizing data and careful reviewed the data to purposefully address the buisness problem in a logical way. Descriptive statistics were also imperative at this point. *Normalizing the data was performed here aswell, however is depicted after some exploratory analysis. 

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

**EXPLORE**

Exploratory Statistical analysis used was: KDE - Kernal Density Estimate was used to obtain PMF - Probability Mass Function, z- Test conducted, P Value derived, R squared Value via OLS was reviewed and in alignment within normal range of 0.493 and Mean Standard Error - MSE and Cross Validation,

**MODEL**

Graphical representations used are in the forms of scatter plots, histograms, linear regression best line of fit using Pandas, Numpy and Matplotlib, mapped residuals to confirm alternate hypothesis. 

**INTERPRET**

(2) Two features that have strong relationships with housing prices:

1. Sqft_living had the strongest linearity compared to sqft_lot which would be a resaonably strong connection to house sales in the area. For example, the larger the lot the higher the price - however this was incorrect, the larger the sqft_living area was directly correlated with the inccreased house sales price. 

2. Final predicted date based on the dataset determined that the *sqft_living, bathrooms) and (sqft-living and grade) both leveled at .076 with strong connections to sale price - however bathrooms were not reviewed in this analysis as a strong correlation to consider. However its is a known factor that when looking for a home, the necessities are: Location, Number of bedrooms and bathrooms, and the size of the lot. 


3 important parameter estimates or statistics found through the data

1. Sqft_living R squared value square = 0.493
2. Grade OLS R squared value =  0.446
3. Pre Processed dummy data predicts price_log at an R squared value of 0.636 with a linear regression prediction array of (540308)


## Deliverables Attached are:

* A **GitHub repository** 
* A **Jupyter Notebook** There are 2 to review as part of this project. Please refer to to Phase2Pro_10 & Phase2_11 
* A **non-technical PDF presentation**



## Paragraph Summary

In Summary this dataset was very interesting. We started out claiming to prove the null hypothesis was correct - which was that sqft_living does not affect the amount of sales or better said increase of house sales price King County area, To which we were successful. The next step was taking a deeper dive in the data set to shape, clean and prep for deeper analysis. From there we were then able to confirm that there was a R squared 62% effective qualitative score of targeted predictors, 

We could plot teh line of regression and when compared to other variables found that the grade which also had a close level of correlation also diplayed a level of gradual increase over time. Meaning that the quality or garde of the home, also impacted the strong desire to purchase the home. 

When we further compared this knowledge after researcvhing some websites on how sqft_lot size impacts the sales of house, we found that the connection was very low.In summary, we are safe to say that there are many determining factors as to why a person purchases a home, perhaps it is the way they feel on teh day, that the house is positioned in an area that makes them feel something special, or that they like to be closer to schools and shops for instance. This data is outside the scope of the data set however would have surprising insights to extract and report on. 

___________________________________________________________________________________________________________________________________________

## For More Information 
___________________________________________________________________________________________________________________________________________

Please review our full analysis in the Jupyter Notebook[Jupyter Notebook] (../PhasePro2_10.ipynb) or our [presentation](./presentation.pdf).

For more information contact **Carla Kirby, ra_carlajoy@yahoo.com** 

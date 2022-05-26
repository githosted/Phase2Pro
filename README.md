# Phase 2 Project


![apartmentliving] (./images/apartmentliving.jpg)

**Phase 2 Project Housing Regression Analysis**

**Author: [Carla Kirby](mailto:ra_carlajoy@yahoo.com)**

There are three deliverables for this project:
## Deliverables Attached 
* A **GitHub repository** - URL 
* A **Jupyter Notebook** - saved as a pdf,uploaded github repo
* A **non-technical presentation** - Phase2Pro.pptx with AUDIO


## Project Overview

For this project, I am using linear regression modeling to analyze house sales in a northwestern county against pricing and researching into sqft_living and sqft_lot to determine which variable has a stronger connection to house sales in the county.


### Business Problem

King County Realty is a newly established local businessin Northwestern Washington.
They are seeking some information regarding what attracts local buyers in this area to purchase new homes.
We wiill inspect the data set to determine what relationships and connections buyers have to purchasing a home and help King County Realty market their new business to suit.


### Key Points

* **The OSEMIN Method was used to establish this project** Refer to [the Data Science Process lesson](https://github.com/learn-co-curriculum/dsc-data-science-processes)

* **Your Jupyter Notebook should demonstrate an iterative approach to modeling.** This means that you begin with a basic model, evaluate it, and then provide justification for and proceed to a new model. After you finish refining your models, you should provide 1-3 paragraphs discussing your final model - this should include interpreting at least 3 important parameter estimates or statistics.

* **Based on the results of your models, your notebook and presentation should discuss at least TWO features that have strong relationships with housing prices.**

## Getting Started

This project has been forked and cloned via [this project repository](https://github.com/githosted/dsc-phase-2-project) to obtain a local copy of the dataset.

This repo is structured as a project repository similar to the structure in [the Phase 1 Project Template](https://github.com/githosted/dsc-project-template). You can do this either by creating a new fork of that repository to work in or by building a new repository from scratch that mimics that structure.

## The Data Process Utilised : OSEMN model (Obtain, Scrub, Explore, Model, Interpret)

**OBTAIN** 

This project contains the King County House Sales dataset, which is found in  `kc_house_data.csv` of the data folder in this repo. The description of the column names can be found in `column_names.md` in the same folder. As with most real world data sets, the column names are not perfectly described, so we have determined and described the data columns below.

Features Ommited: 

* date
* view
* sqft_above
* sqft_basement
* yr_renovated
* zipcode
* lat
* long
* sqft_living15
* sqft_lot15

Data included: 

* price       Purchase price 
* bedrooms    How many beddrooms    
* bathrooms   How many bathrooms    
* sqft_living How many square feet is the living area 
* sqft_lot    How many square feet is the lot     
* floors      How many floors     
* condition   Condition (poor, good, excellent)   
* grade       Indicating Grade / level   
* yr_built    Year house was built  
* zipcode     The zip code in the area   


To avoid multicollinearity, we have limited the frequency of duplicated sqft_variables present in this dataset.
Imported assdociated packages to notebook

**Scrub**

Data cleansing activities conducted: 

* Created test data dummy set
* Removed duplicates, null values, dropped unnecessary columns as they were doubled up information or not relevant to the business problem
* Viewed the shape, Created a copy of data, change type, obtained statistical information for syntax
* Displayed Unique Values 
*


**Explore**

To perform further analysis and gain a clearer understanding of the dataset we have performed the following: 4

* Plotted Kernal Density 
* Created a scatter plot for Linearity
* Mean Squared Error 
* OLS 
* z - Test 
* P value & statistical Significance - Alpha Value of <.05
* Confidence Intervals
* Degree of Freedom 



**Model**

In order to depict for interpretatrion our data model contains: 

* Created a Dummy Test Set 
* Y hat Test
* K Folds 
* Visualised z Statistics 
* Train test split 
*



**Interpret**

In summary, I have determined that the R2 values and the predictions... 
Furthermore, the sqft_lot verses the sqft_living have the closest relationship to the price sales in the King County area. 

## Summary

This project will give you a valuable opportunity to develop your data science skills using real-world data. The end-of-phase projects are a critical part of the program because they give you a chance to bring together all the skills you've learned, apply them to realistic projects for a business stakeholder, practice communication skills, and get feedback to help you improve. You've got this!

## For More Information 

Please review our full analysis in the Jupyter Notebook[Jupyter Notebook] (./PhasePro2.ipynb) or our [presentation](./presentation.pdf).

For more information contact **Carla Kirby, ra_carlajoy@yahoo.com** 
  

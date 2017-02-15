*Project completed as part of Assignment 5 in course MSDS6306: Intro to Data Science at Southern Methodist University*

The project is taking Brooklyn housing sales data from 2016 and comparing square footage to the property sale price.  The project goes through multiple data cleansing and filtering iterations before concluding with its final plot.  Once data is properly formatted and cleansed, the project generates scatter plots comparing square footage to sales price.  These plots start with the original data set containing actual sales and ends with the log10 values of each variable for only 1- 2- and 3- family homes and outliers removed.

The stucture is as follows:

R Project Subdirectories: Source, Paper, Data

Files contained in Source subdirectory:
R_rollingsales_brooklyn.R 

This file contains all of the code used to excute the project.  It includes importing the data csv file, cleansing and filtering the data set, and ploting the cleansed data.

Files contained in Paper subdirectory:
Paper.Rmd

Produces a HTML document of the plot intepretation.


Files contained in Data subdirectory:
rollingsales_brooklyn.csv

This file contains the data set used to execute the project.  Variables inside the data set are as follows...

BOROUGH : int
NEIGHBORHOOD : Factor w/ 61 levels
BUILDING.CLASS.CATEGORY : Factor w/ 44 levels
TAX.CLASS.AT.PRESENT : Factor w/ 10 levels
BLOCK : int 
LOT : int
EASE.MENT : logi
BUILDING.CLASS.AT.PRESENT : Factor w/ 138 levels
ADDRESS : Factor w/ 19705 levels
APARTMENT.NUMBER : Factor w/ 1320 levels
ZIP.CODE : int
RESIDENTIAL.UNITS : Factor w/ 92 levels
COMMERCIAL.UNITS : Factor w/ 23 levels
TOTAL.UNITS : Factor w/ 94 levels
LAND.SQUARE.FEET : Factor w/ 2497 levels
GROSS.SQUARE.FEET : Factor w/ 3187 levels
YEAR.BUILT : int
TAX.CLASS.AT.TIME.OF.SALE : int
BUILDING.CLASS.AT.TIME.OF.SALE: Factor w/ 140 levels
SALE.PRICE : Factor w/ 3516 levels
SALE.DATE : Factor w/ 351 levels

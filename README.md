# Data Science for Public Policy Final Project

## Authors: Adriana Vance, Kyle Kim, Elena Koshkin, Kamiryn Rose

  Our team will examine the relationship between economic status and public health outcomes in the District of Columbia. Approaching this question holistically, we seek to look at several different factors, analyzing economic status through both medical debt and capital flows–loans/investments taken out for specific reasons. 
	We intend to use four different data sources in this project. Firstly, two datasets from the Urban Institute will provide us with information about medical debt along with capital flows (loans/investments) across the DC region. Using ACS data on the median gross rent as a percentage of household income will also provide us with a housing affordability index, which will be useful to demonstrate economic status across DC. The Places dataset from the CDC provides local public health outcome data that we will pair with our medical debt data. This will allow us to analyze the relationship between public health outcomes and medical debt. We can then compare any observed correlation with our estimated relationship between housing affordability and capital flows.
We plan to create several choropleths; one mapping public health outcomes over medical debt and another overlaying investments in the region on top of housing affordability. While these variables do not necessarily measure the same factors/outcomes, we hypothesize that the choropleths will look similar, illustrating the relationship between public health and economic status for DC residents.
 In addition to geospatial visualizations, our team aspires to build and train a machine-learning model that will predict public health outcomes based on distinct economic inputs for various geographic areas in DC. We hope to produce a highly accurate model that forecasts how economic factors may influence DC health by census tract. 
	Though we collectively feel confident in our ability to create choropleths and machine learning models, we anticipate that loading, merging, wrangling, and cleaning the data will pose the biggest technical hurdle in this project. Our data sources are uniform across geographic levels, but merging the datasets seamlessly and understanding how to incorporate multiple sources of data into one machine-learning model will definitely require additional time spent. 


## Data Sources: 

TIGER/Line Shapefile for the District of Columbia from the U.S. Census Bureau
PLACES: Local Data for Better Health | CDC 
B25071_001E: MEDIAN COST RATIO AS A PERCENTAGE OF HOUSEHOLD INCOME IN THE PAST 12 MONTHS
Bank Locations in the Washington, DC, Region | Open Data DC
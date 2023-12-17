# Data Science for Public Policy Final Project

## Authors: Adriana Vance, Kyle Kim, Elena Koshkin, Kamiryn Rose

------------------------------------------------------------------------

-   Because of rendering issues, our final project from our FinalProject.qmd is split into two html files. The html files don't include our interactive map and animated scatter plot.

### Background

In this project, we will examine the relationship between economic status and public health outcomes in the D.C. area. We seek to look at several different factors, analyzing economic status through both mortgage loan debt in the DMV and bank locations in the District of Columbia. The relationship between economic indicators and public health outcomes is well-studied and has great implications for the policy world. Economic success has been shown to be associated with better public health outcomes. Additionally, a healthy economy is usually associated with a healthier U.S. population. On a micro-economic level, this may mean that individual economic hardship is associated with worse public health outcomes. This is the question that our project intends to investigate-- are census tracts with higher levels of mortgage debt, or fewer proximate banks, also more prone to negative public health outcomes such as higher rates of heart disease or depression?

### Data

We obtained the census tract info using the TIGER/Line Shapefile for the District of Columbia from the U.S. Census Bureau. We installed this data through the library(tigris) command, and we manually selected the Maryland tract, Virginia tract, and DC tract to get a picture of the whole DMV area.

The CDC PLACES dataset uses small-area estimation methods to provide a model-based mapping of 36 different chronic disease-related measures throughout the United States. These measures include 13 health outcomes, 9 prevention practices, 4 health risk behaviors, 7 disabilities, and 3 health statuses, used to estimate the rates of various chronic conditions by census tract level. The CDC PLACES data was downloaded from the CDC website and sifted to select data from exclusively DC, Maryland, and Virginia. Please download the CSV file provided, "PLACES.csv", to load the correct dataframe.

The debt-to-income ratio dataset comes from the Federal Housing Finance Agency, which records data about home purchase loans. This dataset has information on individual loans taken out for single-family homes, along with specifications of census tracts. The data also include the debt-to-income ratio of each borrower, which is an indication of how much debt the borrower has taken on in relation to their income. The debt-to-income ratio (or DTI) is generally regarded as a reliable indicator of a borrower's financial health, or ability to pay monthly debt payments. Other useful variables in this dataset that will be used in our analysis are census tract indicators, the percentage of minorities in a given census tract, tract median income, and mortgage amount.

We chose to download the dataset from 2021, as this will reflect the same year as our CDC health outcomes dataset. To download the correct dataset for our analysis, go to this [link:](https://www.bcbs.com/the-health-of-america/articles/healthy-communities-mean-better-economy) and download the ZIP file for the 2021 Freddie Mac dataset. Alternatively, you can use the txt file we included with our submission titled "debt_to_income.txt"

The banks dataset provides the exact locations of banks in the District of Columbia. The data is available for access on [Washington DC's open data portal](https://opendata.dc.gov/datasets/DCGIS::bank-locations/explore?location=39.007423%2C-76.009578%2C8.59). The locations of the banks are provided by the Department of Insurance Securities and Banking (DISB). The dataset is updated irregularly, as needed, and provides the latitude and longitude coordinates of the banks across DC.

### Data Interpretation and Analysis

Our research aimed to document and analyze the relationships between health outcomes, economic conditions, geography, and demographics across various census tracts in the DMV area. Through this exploration, we found several patterns suggesting correlative relationships that could be invaluable when guiding policy decisions and healthcare initiatives.

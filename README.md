# ps239T-final-project
For PS239T


# Short Descriotion
Political geography of populist candidate in the United States. A county-level analysis of Donald Trump's winning margin in the 2016 Presidential Election and Mitt Romeney's margin in the 2012 Election with respect to the socio-economic indicators in the county during the period. 

# Dependencies
R version 3.2.3 (2015-12-10)  
Python, version 3.5, Anaconda

# Files 

## Data
1. census.csv: Contains data from the the Census API collected and edited via Census_API-without_key.ipynb. Based on the American Community Servey 5 year data 2014. For the choice of variables, prease refer to the code Census_API-without_key.ipynb.
2. census2010.csv: Contains data from the the Census API collected and edited via Census_API-without_key.ipynb. Based in the American Community Servey 5 year data 2010.
3. election.csv: County level election result data for 2012 and 2016 presidential election. The data that Tony McGovern has compiled by scraping through townhall.com home page, collected and edited via Final Project.Rmd. Original one available at: https://github.com/tonmcg/County_Level_Election_Results_12-16
4. mergeddata.csv: census.csv, census2010.csv and election.csv merged by state and county identification via Final Project.Rmd. Added some intertemporal variables. It includes county-year values for two time periods 2010/2014 for all the counties in the US. 
5. swingstate.csv: The final Analysis Dataset derived from the mergeddata.csv, edited via Final Project.Rmd. It includes county-year values for two time periods 2010/2014 for 8 major swing states in 2016 presidential election. 


## Code
1. Census_API-without_key.ipynb: Collects data from Census API, create some variables and exports data to the file census.csv, census2014.csv
2. Final Project.Rmd:  Loads, cleans, and merges the raw electoral data and census datasets into the "total2" and "swing2" Dataset;  Producing the tables and visualizations.

## Results
1. Final_Project.pdf: Contains numerous plots using "ggplot" and one regression table for 3 models, using "stargazer"

# More information
N/A




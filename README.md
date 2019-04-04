# Project-1
Andrew Desa, John Palalia, Chris Catolico

Question: Is there a correlation between CA academic performance index and local housing prices?

Null Hypothesis: There is no correlation between CA academic performance index and local housing prices.

CA academic Performance: https://www.cde.ca.gov/re/pr/api-datarecordlayouts.asp
House Prices: Zillow API
Zip Codes for Education data: Google Geolocations API

Primary Files:
1. EducationData.ipynb: Reads in Education Data pulled from CDE website. Pulls in zipcode for schools. Output data to 'APIScores.csv'
2. Zillow Data.ipynb: Pulls Zillow data from API. Output data to 'ZillowData.xml'
3. Merge Data.ipynb: Merge together APIScores.csv and ZillowData.xml to create final database.
4. DataAnalysis.ipynb: Summarize data and run tests (regression/ANOVA) to determine if null hypothesis can be rejected.
5. User Application.ipynb: App which allows user to enter a zip code and retrieve average API score and housing price in that area.

Output Files:
1. BoxPlot.png: boxplot produced by DataAnalysis.ipynb
2. ScatterPlot.png: scatterplot produced by DataAnalysis.ipynb



# Comparing Baltimore & Los Angeles Household and Male Income with Incarceration-Rate
Goal:

The focus of this project is to establish the relationship between average male income and incarceration rate in Los Angeles, CA and Baltimore, MD.  I did this by pulling data from the Opportunity Atlas on household income, male income, and incarceration rate for the two cities. I had the the goal of not only confirming the correlation between low household income and higher incarceration rates, but I also wanted to see if a lower male income had a larger correlation with higher incarceration rates.  Along the way I would also be able to compare incarceration rates, household income, and male income across the two cities.

Results:

My initial thought that Los Angeles would have both higher incomes and lower incarceration rates than Baltimore was confirmed. In fact, the average household in Los Angeles is more than $10,000 higher and the incarceration rate more than 3% lower than those in Baltimore. The chart below shows this information.  

![chartimage](https://github.com/diallo-scott/comparing-baltimore-losangeles-household-and-male-income-with-Incarceration-Rate/blob/master/Average%20Household%20Income%20and%20Incarceration.png)

When considering male income and incarceration rates, I was surprised at the results. Male income was similar across the two cities with Los Angeles' result being just $2600 higher. Given that the difference in male income between the two cities is not very sigificant, one may expect similar incarceration rates, yet this was not the case.  Baltimore's overall incarceration rate is 4.6% but that of Los Angeles is 1.6%.  The chart below shows this information.

![chartimage](https://github.com/diallo-scott/comparing-baltimore-losangeles-household-and-male-income-with-Incarceration-Rate/blob/master/Male%20Income%20and%20Incarceration%20Rate%20in%20Los%20Angeles%20and%20Baltimore.png)

These results proved that male income may not be the best metric to use as a gauge for how high incarceration rates may be.  At least when comparing Baltimore and Los Angeles, we can see that household income has more of a link with the incarceration rate than just the male income.

Step-by-step Guide to Excel Manipulation for Pictured Charts:
1. Download data on household income, male income, and incarceration rate from the Opportunity Atlas for both Los Angeles and     Baltimore
2. Use VLOOKUP function to aggregate data for each city on individual sheets in the same workbook, so that we now have one tab for Los Angeles and one for Baltimore
3. Create pivot table for each of the two sheets
4. Now we can easily see the average household income, male income, and incarceration rates for individual tracts in each city and the city as a whole.
5. Use the entire city averages to create two charts: one that plots household income and incarceration rate together and another with male income and incarceration

Link to Excel Spreadsheet with Analyzed Data :
https://github.com/diallo-scott/comparing-baltimore-losangeles-household-and-male-income-with-Incarceration-Rate/blob/master/Business%20Analytics%20Mini%20Project%201.xlsx
Note: The visualizations above can be found in the tab entitled "Bmore & LA Male Income v Prison". This workbook also contains tabs with other data visualizations that did not directly contribute to the focused results presented above.  These visualizations include household income and incarceration rates for the individual tracts of each city.  These were not pictured above due to the fact they are much harder to read. 

Link to Spreadsheets with Raw Data:
https://github.com/diallo-scott/comparing-baltimore-losangeles-household-and-male-income-with-Incarceration-Rate/tree/master/Raw%20Excel%20Data
Note: The aggregated raw data can also be found on tabs in the spreadsheet with the analyzed data.




Source:
https://www.opportunityatlas.org/

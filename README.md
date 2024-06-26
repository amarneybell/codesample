# codesample

The following is a sample of code I used to download, clean, and merge US Census Bureau data for my undergraduate thesis. This data was crucial for creating the control variables in my regression analysis. In the raw data frames, each unit of analysis is a Community Statistical Area (CSA), so the data is in wide form. For my analysis, I wrote a function to easily transform the data to long form, making each unit a CSA in a given year. Additionally, I had to correct CSA names for some of the race breakdown data and separately import and append missing data for the age group breakdowns. These steps were essential to ensure the final data panel was balanced, maximizing the precision of my regression. 

The sample can be found in the document titled `Sample.Rmd.` 

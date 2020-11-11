# my_project_1

Project 1 Title: COVID 19 and Food Insecurity in the United States: A County Level Analysis for Infection Rate, Hospitalization, and Mortality
 
Background: About 40% of Americans cannot afford a $400 unexpected expense in the year 2019.[i] Many households are living paycheck to paycheck with little savings set aside for emergencies. Particularly, food insecurity is common in the United States; millions of households struggle to pay for food and don’t have proper access to healthy food.[ii] Moreover, the recent widespread health crisis of COVID-19 across the whole country forced almost 90% of the population to stay at home[iii], and within weeks, more than 17 million individuals filed for unemployment benefits.[iv] It is expected that the unemployment rate will reach a historically high level that has not been seen since the great depression back in the 1940s.

Motivation: It is likely that this health crisis will cause an unprecedented economic downturn, and as a result, more families will face difficulties to meet their financial obligations for daily living necessities, i.e. food and other monthly bills. However, little evidence is available for the potential impact of COVID-19 on food insecurity in the United States. Because food insecurity is already a problem, the COVID-19 outbreak will only exaggerate the problem. 

 
Objective: To examine associations between food insecurity rate and COVID-19 in terms of infection rate, hospitalizations, and mortality rate at county level. We set this objective because food insecurity is a good indicator for low socioeconomic status, and is generally associated with poorer nutrition intake, lower level of physical activity, more comorbid conditions, and lower level of health insurance coverage. Therefore, we expect that counties with higher food insecurity levels may also experience a wider spread of COVID-19, higher hospitalization rate, and higher mortality rate.
 
Main hypothesis:
 	COVID-19 infection/hospitalization/mortality rates are higher in counties with more severe food insecurities compared to counties with lower level of food insecurities in the U.S. Other socio-economic status indicators at county level, e.g. percent of population with less than high school education, percent living under Federal Poverty Level, and percent of households without transportation vehicles are all associated with more impact due to COVID-19.
 Null hypothesis: 
There is no correction between food insecurity, socio-economic status indicators and COVID-19 infection/hospitalization/mortality rates in the US.
		
Data sources: We will retrieve data from three separate sources as illustrated below:
1)	Food insecurity data: county level food insecurity rate and number of individuals experiencing food insecurity will be obtained from FeedingAmeria (https://map.feedingamerica.org/); We already have the data in excel format obtained from FeedingAmerica research department.
 

2) 	COVID-19 data: Johns Hopkins University COVID-19 (https://coronavirus.jhu.edu/us-map); These data is publicly available at github: https://github.com/CSSEGISandData/COVID-19


3) 	County level socioeconomic measures from the current population survey (CPS, https://www.census.gov/programs-surveys/cps.html). We will search the census website and obtain relevant measurements.  
 
Main outcomes: Map for food insecurity at county level in the United States; Map for COVID-19 infection rate at county level in the United States; Overlapping two maps to get insides about their associations; Stratifying the analyses by other socioeconomic measurements.
 
 
Analyses plan:
First step, we will utilize what we learned in Python and Pandas to import food insecurity data and translate it into a county level heat map to show patterns of food insecurity in the United States.
 
Second step, we will use what we learned about API to find other socioeconomic status measurements (e.g. percent of population without high school education) from the census website.
 
Third step, we will retrieve data from Johns Hopkins University COVID-19 data (available through their public github account) and translate it into a heat map for county level infection rate, hospitalization rate, and mortality rate.
 
Fourth step, we will conduct three separate regression analyses using COVID-19 infection/hospitalization/mortality rates as outcomes, respectively, and using county level food insecurity level as well as other socioeconomic status indicators as explanatory variables, to formally test our hypotheses, including test statistics and p-values from the regression results.
 
Limitations:
Our project will focus on county level analyses, and we cannot perform person level analyses, and therefore we cannot control for person level variables, such as age, comorbid conditions, and their family income, etc. Moreover, the most recent data available from FeedingAmerica is year 2017, while COVID-19 data will be from year 2020. However, food insecurity rates at county level are relatively stable over the years, and we will make the assumption that year 2020 food insecurity remains the same as year 2017. Lastly, we mainly are looking for associations between food insecurity and COVID-19 infection as well as health outcomes, we can not establish causations.

 
[i]https://www.federalreserve.gov/publications/files/2017-report-economic-well-being-us-households-201805.pdf
 
[ii]https://www.ers.usda.gov/topics/food-nutrition-assistance/food-security-in-the-us/key-statistics-graphics.aspx
 
[iii] https://www.cnn.com/2020/03/23/us/coronavirus-which-states-stay-at-home-order-trnd/index.html
 
[iv] https://www.dol.gov/ui/data.pdf



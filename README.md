# Covid Data Exploration

## Dataset

The data consists of information regarding Covid world wide and can be found at: https://raw.githubusercontent.com/owid/covid-19-data/master/public/data/owid-covid-data.csv

The description of the fields can be found at: https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-data-codebook.md

With each run of the Notebook, the newest Covid data is downloaded.

For the last plot, I used Swiss data regarding the number of tests being done. I only have the link to a Tableau visualization and extracted the data from here: https://covid-19-schweiz.bagapps.ch/de-3.html. This data is as of June 23rd 2020.


## Summary of Findings

In the exploration, I visualized the distribution on total Covid cases and deaths, new cases and new deaths. I also visualized the distribution of the factors I thought influence the spread or the mortality rate of Covid: beds in hospital per thousand, population density, GDP per capita and diabetes prevalence. Out of all these variables, only GDP per capita seemed to be correlated to the total cases of Covid. I added the 'continent' categorical dimension in the plot as well to better see which continents have higher GDP per capita and are more affected by Covid. The results are better seen on a log scale.

I also had a closer look at how Covid numbers changed over time, since December 2019 and more than half a year later, June 2020. I 'zoomed in' to the situation in Switzerland, for which I displayed the number of positive test results vs the number of negative test results, and the rolling average of new cases on a 14-days window.

Outside of the main variables of interest, I looked at the distribution of the stringency index, and the most affected countries currently, where it is best to avoid traveling.


## Key Insights for Presentation

For the presentation (the "Covid_Data_Analysis_Part_2" ipynb file), I start from the 'world' view, how Covid has spread over time and in which continents, then I look at the distribution of the main variables of interest: total Covid cases and deaths, new cases and new deaths. I continue to present how the countries have applied measures to stop the spread of Covid and the most affected countries currently. In the end, I focus on Switzerland to better illustrate the current situation in the country where I live.

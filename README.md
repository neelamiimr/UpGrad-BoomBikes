## BoomBikes - Bike Sharing demand forecast
Problem statement: BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic.

Resolution needed: Mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end

Strategy: A. Data analysis

i. Understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19
ii. Understand the factors on which the demand for these shared bikes depends



## Table of Contents
## General information
Multi-linear regression was run to understand the significant variables impacting Boom bikes demand
## [Technologies Used]

    numpy - version 1.20.3
    pandas - version 1.3.4
    matplotlib - version 3.4.3
    plotly - version 5.6.0
    seaborn - version 0.11.2
    statsmodels - version 0.12.2
    sklearn - version 0.24.2
    scipy - version 1.7.1

## Conclusions
The equation for the best fiited line is : cnt = 0.53 + 0.24yr + 0.07mnth_sep + 0.06weekday_Saturday + 0.056workingday -0.04season_summer -0.07season_winter -0.089weathersit_Mist -0.1mnth_jan -0.19 windspeed-0.26season_spring-0.30*weathersit_Light_Snow

    1.Year, September month, weekday of Saturday, working day is positively impacting the demand
    2. Summer season, winter season, misty weather situation, windspeed, spring season and Light snow are negatively proportional and negatively impacting demand




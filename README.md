## BoomBikes - Bike Sharing demand forecast
Problem statement: BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic.

Resolution needed: Mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end

Strategy: A. Data analysis

i. Understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19
ii. Understand the factors on which the demand for these shared bikes depends



## Table of Contents
* General information
Multi-linear regression was run to understand the significant variables impacting Boom bikes demand
* [Technologies Used]

    numpy - version 1.20.3
    pandas - version 1.3.4
    matplotlib - version 3.4.3
    plotly - version 5.6.0
    seaborn - version 0.11.2
    statsmodels - version 0.12.2
    sklearn - version 0.24.2
    scipy - version 1.7.1

* [Conclusions]
The equation for the best fiited line is : cnt = 0.53 + 0.24yr + 0.07mnth_sep + 0.06weekday_Saturday + 0.056workingday -0.04season_summer -0.07season_winter -0.089weathersit_Mist -0.1mnth_jan -0.19 windspeed-0.26season_spring-0.30*weathersit_Light_Snow

    1.Year, September month, weekday of Saturday, working day is positively impacting the demand
    2. Summer season, winter season, misty weather situation, windspeed, spring season and Light snow are negatively proportional and negatively impacting demand



<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis
- Conclusion 2 from the analysis
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
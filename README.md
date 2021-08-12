# Airbnb_study
This repository contains a course project report: Compare Influencing Factors of Airbnb Penetration in Three U.S. cities, which studies the Airbnb penetration in Chicago, Washington D.C. and Los Angeles. The number of Airbnb listings in each census tract are used to measure the level of Airbnb penetration. Spatial regression models and OLS models are built to explore the influencing factors of Airbnb penetration in the three cities, considering the spatial dependence effect of th Airbnbs.

## Data
Three catoegories of indicators, including geographic, demographic and socio-economic factors are selected as the potential influencing factors of Airbnb penetration. All of the data of the indicators and Airbnb listings for the three cities are included in this repository. We use data of 2018 to conduct the study.

## Main findings
The study finds that there is strong spatial dependence in Airbnb penetration in all of the three cities by conducting Global Moran’s I test and the Lagrange Multiplier test. Rather than a merely geographical clustering of the sources of the behaviour of interest, Airbnb actually interact with each other and might tend to cluster together because of the agglomeration effect that attracts more customers.

By conducting explanatory analysis using OLS regression and spatial regression, this study also finds that there are some common influencing factors of Airbnb penetration among the three different cities (Chicago, Los Angeles and Washington D.C.), including population, proportion of young people (under 34 years old), and number of bus stops (table 8). There are also some other factors such as Bohemian Index, Talent Index, Proportion of owner-occupied residences, and Median Household Value have significant influences on Airbnb penetration in two of the cities (table 8). These common factors indicate that Airbnb penetration is more likely to happen in the areas which are populous, vibrant, and with a higher proportion of young people and creative class. We also notice that proportion of owner-occupied residences has negative influences in Chicago but has positive influence in Washington D.C.. Quattrone et al. (2008) found that in London there is there is a statically significant negative relation between the proportion of owner-occupied residences and Airbnb penetration, because Airbnb hosts tend to rent rather than own the property. Our analysis only partially confirms this result, and the reasons of the positive significant influence in Washington D.C. would be explored further.

The full PDF report can be find in this reporsitory.

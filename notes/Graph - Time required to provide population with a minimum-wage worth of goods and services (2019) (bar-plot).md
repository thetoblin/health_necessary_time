# Graph - Time required to provide population with a minimum-wage worth of goods and services (2019) (bar-plot)
#github-health-necessary-time #bar-plot #barplot


**Description**
Comparing 1) the number of hours required (per capita and per person in the working-age population (ages 15-64)) to provide everyone in the population of a given country with an annual minimum-wage worth of goods and services with the country's average productivity (GDP per hour), with 2) the country's average working hours. For the year 2019.


**Variables used**
- [[minwage_nectime_weekly_per_capita_df (variable) (hours per capita per week)#The number of hours per capita per week assuming 52 weeks per year required to provide everyone in the population of a given country with an annual minimum-wage worth of goods and services given the country's average productivity GDP per hour Root sources PWT10 0 OECD 2021 user assumed number of weeks per year]]
- [[minwage_nectime_weekly_perworkingageperson_df (variable) (hours per week per working-age person (ages 15-64))#The number of hours per week per working-age person ages 15-64 required to provide everyone in the population of a given country with an annual minimum-wage worth of goods and services given the country's average productivity GDP per hour Root sources PWT10 0 OECD 2021 OECD 2022 user assumed number of weeks per year]]
- [[workhours_weekly_avg_df (variable) (hours per week)#average weekly hours worked by persons engaged employees and self-employed Root sources - PWT10 0]]


**Root sources**
- [[Reference - Penn World Table 10.0 (Dataset) (Groningen Growth and Development Centre, 2021)]]
- [[Reference - Minimum Wages at Current Prices in NCU (Database) (OECD, 2021) (accessed 18 April 2022)]]
- [[Reference (dataset) - “Working Age Population” (OECD) (accessed June 29, 2022)]]
- [[Reference - The Next Generation of the Penn World Table (Feenstra, Inklaar, Timmer, 2015)]] (must be cited since [[It is required to cite (Feenstra et. al., 2015) when using the Penn World Table 10.0 (Dataset) (PWT 10.0 (Website), 2021)]])
- User assumption of the number of weeks per year, given by [[weeks_per_year=52 (variable) (user assumption) (weeks)#The user-defined number of weeks per year]]


**Produced by code**
![[minwage_barplot.py]]


**Image**
![[minwage_barplot_ver1.0.png]]


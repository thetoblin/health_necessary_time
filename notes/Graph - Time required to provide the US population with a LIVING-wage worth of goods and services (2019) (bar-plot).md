# Graph - Time required to provide the US population with a LIVING-wage worth of goods and services (2019) (bar-plot)
#github-health-necessary-time #bar-plot #barplot


**Description**
Comparing 1) the number of hours required (per capita and per working-age person (ages 15-64)) to provide every individual in the United States with an annual living-wage worth of goods and services with the country's average productivity (GDP per hour), and 2) the country's average working hours. The living wage annual income assumes that each individual has the needs of a single adult, neglecting economies of scale in consumption that arise from e.g. sharing a household. For the year 2019.

**Variables used**
- [[livwage_nectime_weekly_percapita_USA_df (variable) (hours per year per capita)]]
- [[livwage_nectime_weekly_perworkingageperson_USA_df (variable) (hours per week per working-age person)]]
- [[livwage_annualcost_percapita_USA_df (variable) (US dollars at current prices)]]
- [[workhours_weekly_avg_df (variable) (hours per week)]]


**Root sources**
- [[Reference - Living Wage Calculator (Glasmeier, 2022) (data retrieved 26 August 2022)]]
- [[Reference - US Census Bureau dataset “National and State Population Estimates" from database “National Population Totals; 2010-2020” (July 2021)]]
- [[Reference - Penn World Table 10.0 (Dataset) (Groningen Growth and Development Centre, 2021)]]
- [[Reference - The Next Generation of the Penn World Table (Feenstra, Inklaar, Timmer, 2015)]]
- User assumption of the number of weeks per year, given by [[weeks_per_year=52 (variable) (user assumption) (weeks)#The user-defined number of weeks per year]]
- User assumption of the number of workhours per week, given by [[workhours_per_week=40 (variable) (user assumption) (hours per week)]].


**Produced by code**
![[livwage_barplot.py]]


**Image**
![[livwage_barplot.png]]


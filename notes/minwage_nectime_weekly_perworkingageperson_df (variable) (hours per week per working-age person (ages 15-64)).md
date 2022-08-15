# minwage_nectime_weekly_perworkingageperson_df (variable) (hours per week per working-age person (ages 15-64))
# The number of hours per week per working-age person (ages 15-64) required to provide everyone in the population of a given country with an annual minimum-wage worth of goods and services given the country's average productivity (GDP per hour). Root sources PWT10.0, (OECD, 2021), (OECD, 2022), user assumed number of weeks per year
#github-health-necessary-time
#code-variable #name #code #python #variable

**Name**
`minwage_nectime_weekly_perworkingageperson_df`

**Unit**
Hours per week per working-age person (ages 15-64).

**Description**
The number of hours per week per working-age person (ages 15-64) required to provide everyone in the population of a given country with an annual minimum-wage worth of goods and services given the country's average productivity (GDP per hour).

**Root source(s)**
- [[Reference - Penn World Table 10.0 (Dataset) (Groningen Growth and Development Centre, 2021)]]
- [[Reference - Minimum Wages at Current Prices in NCU (Database) (OECD, 2021) (accessed 18 April 2022)]]
- [[Reference (dataset) - “Working Age Population” (OECD) (accessed June 29, 2022)]]
- User assumption, given by [[weeks_per_year=52 (variable) (user assumption) (weeks)#The user-defined number of weeks per year]]

**Calculation**
`minwage_nectime_weekly_perworkingageperson_df = minwage_nectime_annual_perworkingageperson_df / weeks_per_year`

where
- `minwage_nectime_annual_perworkingageperson_df` is given by [[minwage_nectime_annual_perworkingageperson_df (variable) (hours per year per working-age person (ages 15-64))#The number of hours per year per working-age person ages 15-64 required to provide everyone in the population of a given country with an annual minimum-wage worth of goods and services given the country's average productivity GDP per hour Root sources PWT10 0 OECD 2021 OECD 2022]], and
- `weeks_per_year` is given by [[weeks_per_year=52 (variable) (user assumption) (weeks)#The user-defined number of weeks per year]]

**File(s) where variable is declared**
![[minwage_estimate.py]]

**Object type**
class 'pandas.core.frame.DataFrame'

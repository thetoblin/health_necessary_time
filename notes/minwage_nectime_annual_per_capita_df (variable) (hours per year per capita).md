# minwage_nectime_annual_per_capita_df (variable) (hours per year per capita)
# The annual number of hours per capita required to provide every individual in the population of a given country with an annual minimum-wage worth of goods and services given the country's average productivity (GDP per hour). Root sources (OECD, 2021) and PWT10.0
#github-health-necessary-time
#code-variable #name #code #python #variable

**Name**
`minwage_nectime_annual_per_capita_df`

**Unit**
Hours per year per capita.

**Description**
The annual number of hours per capita required to provide every individual in the population of a given country with an annual minimum-wage worth of goods and services given the country's average productivity (GDP per hour).

**Root source(s)**
- [[Reference - Penn World Table 10.0 (Dataset) (Groningen Growth and Development Centre, 2021)]]
- [[Reference - Minimum Wages at Current Prices in NCU (Database) (OECD, 2021) (accessed 18 April 2022)]]

**Calculation**
`minwage_nectime_annual_per_capita_df = minwage_nectime_annual_total_df / population.df`

Where
- `minwage_nectime_annual_total_df` is given by [[minwage_nectime_annual_total_df (variable) (hours per year)]], and
- `population` is given by [[population (variable) (Penn World Table 10.0) (number of individuals)]]

**File(s) where variable is declared**
![[minwage_estimate.py]]

**Object type**
class 'pandas.core.frame.DataFrame'

# minwage_nectime_annual_perworkingageperson_df (variable) (hours per year per working-age person (ages 15-64))
# The number of hours per year per working-age person (ages 15-64) required to provide every individual in the population of a given country with an annual minimum-wage worth of goods and services given the country's average productivity (GDP per hour). Root sources PWT10.0, (OECD, 2021), (OECD, 2022)
#github-health-necessary-time
#code-variable #name #code #python #variable

**Name**
`minwage_nectime_annual_perworkingageperson_df`

**Unit**
Hours per year per working-age person (ages 15-64).

**Description**
The number of hours per year per working-age person (ages 15-64) required to provide every individual in the population of a given country with an annual minimum-wage worth of goods and services given the country's average productivity (GDP per hour).

**Root source(s)**
- [[Reference - Penn World Table 10.0 (Dataset) (Groningen Growth and Development Centre, 2021)]]
- [[Reference - Minimum Wages at Current Prices in NCU (Database) (OECD, 2021) (accessed 18 April 2022)]]
- [[Reference (dataset) - “Working Age Population” (OECD) (accessed June 29, 2022)]]

**Calculation**
`minwage_nectime_annual_perworkingageperson_df = minwage_nectime_annual_total_df / workagepop_df`

Where
- `minwage_nectime_annual_total_df` is given by [[minwage_nectime_annual_total_df (variable) (hours per year)]], and
- `workagepop_df` is given by [[workagepop_df (variable) (number of individuals)#The working-age population ages of 15-64 in units of number of individuals Root source OECD 2022 PWT10 0]]

**File(s) where variable is declared**
![[minwage_estimate.py]]

**Object type**
class 'pandas.core.frame.DataFrame'

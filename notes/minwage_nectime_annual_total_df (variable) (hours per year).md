# minwage_nectime_annual_total_df (variable) (hours per year)
# The total number of hours per year required to provide every individual in the population (of a given country) with an annual minimum-wage worth of goods and services, given the country's average productivity (GDP per hour). Root sources (OECD, 2021) and PWT10.0
#github-health-necessary-time
#code-variable #name #code #python #variable

**Name**
`minwage_nectime_annual_total_df`

**Unit**
Hours per year.

**Description**
The total number of hours per year required to provide every individual in the population (of a given country) with an annual minimum-wage worth of goods and services, given the country's average productivity (GDP per hour).

**Root source(s)**
- [[Reference - Penn World Table 10.0 (Dataset) (Groningen Growth and Development Centre, 2021)]]
- [[Reference - Minimum Wages at Current Prices in NCU (Database) (OECD, 2021) (accessed 18 April 2022)]]

**Calculation**
`minwage_nectime_annual_total_df = minwage_goods_and_services_annual_totalpop_df / productivity_df`

Where
- `minwage_goods_and_services_annual_totalpop_df` is given by [[minwage_goods_and_services_annual_totalpop_df (variable) (national currency at current prices)]], and
- `productivity_df` is given by [[productivity_df (variable) (national currency at current prices)#Productivity GDP per hour worked measured in national currency at current prices by persons engaged employees and self-employed Root sources PWT10 0]].

**File(s) where variable is declared**
![[minwage_estimate.py]]

**Object type**
class 'pandas.core.frame.DataFrame'

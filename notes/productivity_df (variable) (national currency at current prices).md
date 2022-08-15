# productivity_df (variable) (national currency at current prices)
# Productivity (GDP per hour worked, measured in national currency at current prices) by persons engaged (employees and self-employed). Root sources PWT10.0
#github-health-necessary-time
#code-variable #name #code #python #variable

**Name**
`productivity_df`

**Unit**
National currency at current prices.

**Description**
Productivity (GDP per hour worked, measured in national currency at current prices) by persons engaged (employees and self-employed).

**Root source(s)**
- [[Reference - Penn World Table 10.0 (Dataset) (Groningen Growth and Development Centre, 2021)]]

**Calculation**
`productivity_df = gdp_current_natprices.df / workhours_annual_total_df`

Where
- `gdp_current_natprices` is given by [[gdp_current_natprices (variable) (Penn World Table 10.0) (national currencies at current prices)]], and
- `workhours_annual_total_df` is given by [[workhours_annual_total_df (variable) (hours per year)#The total number of hours worked in a given country by persons engaged employees and self-employed Root sources - PWT10 0]]

**File(s) where variable is declared**
![[derived_data.py]]

**Object type**
class 'pandas.core.frame.DataFrame'

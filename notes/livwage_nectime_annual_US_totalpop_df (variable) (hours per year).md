# livwage_nectime_annual_US_totalpop_df (variable) (hours per year)
# The total annual number of hours required to provide every individual in the US population with an annual living-wage worth of goods and services given the country's average productivity (GDP per hour)
#github-health-necessary-time
#code-variable #name #code #python #variable

**Name**
`livwage_nectime_annual_US_totalpop_df`

**Unit**
Hours per year.

**Description**
The total annual number of hours required to provide every individual in the US population with an annual living-wage[^livwage] worth of goods and services given the country's average productivity (GDP per hour). The living wage[^livwage] annual income assumes that each individual has the needs of a single adult, neglecting economies of scale in consumption[^ecoscale] that arise from e.g. sharing a household.

**File(s) where variable is declared**
![[livwage_estimate.py]]

**Calculation**
Calculated by dividing the value to be produced (USD) by the productivity (USD/hour).

`livwage_nectime_annual_US_totalpop_df = livwage_goods_and_services_US_annual_totpop_df / productivity_df.loc['USA']`

Where
- `livwage_goods_and_services_US_annual_totpop_df` is given by [[livwage_goods_and_services_US_annual_totpop_df (variable) (USD per year, current prices)]], and
- `productivity_df` is given by [[productivity_df (variable) (national currency at current prices)]].


**Root source(s)**
- [[Reference - Living Wage Calculator (Glasmeier, 2022) (data retrieved 26 August 2022)]]
- [[Reference - US Census Bureau dataset “National and State Population Estimates" from database “National Population Totals; 2010-2020” (July 2021)]]
- [[Reference - Penn World Table 10.0 (Dataset) (Groningen Growth and Development Centre, 2021)]]
- User assumption of the number of weeks per year, given by [[weeks_per_year=52 (variable) (user assumption) (weeks)#The user-defined number of weeks per year]]
- User assumption of the number of workhours per week, given by [[workhours_per_week=40 (variable) (user assumption) (hours per week)]].

**Object type**
class 'pandas.core.frame.DataFrame'


[^ecoscale]: For a definition of *economies of scale in consumption*, see [['Economies of scale in consumption' as the possible decreases in the cost per person of maintaining a given material standard of living as the number of household members increase (p.1301, Nelson, 1988)]].

[^livwage]: For a definition of *living wage*, see [['Living wage' as the minimum income necessary for an employee to be able to satisfy their basic needs (Wikipedia, 2022)]].
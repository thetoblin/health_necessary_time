# livwage_goods_and_services_US_annual_totpop_df (variable) (USD per year, current prices)
# The living wage annual income of the total US population for a number of years
#github-health-necessary-time
#code-variable #name #code #python #variable

**Name**
`livwage_goods_and_services_US_annual_totpop_df`

**Unit**
US dollars per year, current prices.

**Description**
The living wage[^livwage] annual income of the total US population, assuming that each individual has the needs of a single adult (neglecting economies of scale in consumption[^ecoscale] that arise from e.g. sharing a household), specified in units of US dollars per year.

**File(s) where variable is declared**
![[livwage_estimate.py]]

**Calculation**
Calculated by summing the annual living wage income for each of the US states for each year.

`livwage_goods_and_services_US_annual_totpop_df	= pandas.DataFrame(livwage_goods_and_services_USstates_annual_totalpop.sum()).transpose()`

Where
- `livwage_goods_and_services_USstates_annual_totalpop` is given by [[livwage_goods_and_services_USstates_annual_totalpop (variable) (USD per year, current prices)]].


**Root source(s)**
- [[Reference - Living Wage Calculator (Glasmeier, 2022) (data retrieved 26 August 2022)]]
- [[Reference - US Census Bureau dataset “National and State Population Estimates" from database “National Population Totals; 2010-2020” (July 2021)]]
- User assumption of the number of weeks per year, given by [[weeks_per_year=52 (variable) (user assumption) (weeks)#The user-defined number of weeks per year]]
- User assumption of the number of workhours per week, given by [[workhours_per_week=40 (variable) (user assumption) (hours per week)]].

**Object type**
class 'pandas.core.frame.DataFrame'


[^ecoscale]: For a definition of *economies of scale in consumption*, see [['Economies of scale in consumption' as the possible decreases in the cost per person of maintaining a given material standard of living as the number of household members increase (p.1301, Nelson, 1988)]].

[^livwage]: For a definition of *living wage*, see [['Living wage' as the minimum income necessary for an employee to be able to satisfy their basic needs (Wikipedia, 2022)]].
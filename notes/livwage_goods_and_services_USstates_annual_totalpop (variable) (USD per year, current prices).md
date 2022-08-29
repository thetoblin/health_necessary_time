# livwage_goods_and_services_USstates_annual_totalpop (variable) (USD per year, current prices)
# The living wage annual income of the population of the US states
#github-health-necessary-time
#code-variable #name #code #python #variable

**Name**
`livwage_goods_and_services_USstates_annual_totalpop`

**Unit**
US dollars per year, current prices.

**Description**
The living wage[^livwage] annual income of the populations in the US states, assuming that each individual has the needs of a single adult (neglecting economies of scale in consumption[^ecoscale] that arise from e.g. sharing a household), specified for each US state in units of US dollars per year.

**File(s) where variable is declared**
![[livwage_estimate.py]]

**Calculation**
Calculated by, for each year, multiplying the annual living-wage income for each state by the number of individuals in that state.

`livwage_goods_and_services_USstates_annual_totalpop = liv_grossincome_USstates_annual_df * population_USstates_df`

Where
- `liv_grossincome_USstates_annual_df` is given by [[liv_grossincome_USstates_annual_df (variable) (USD per year, current prices)]], and
- `population_USstates_df` is given by [[population_USstates_df (variable) (US Census Bureau, 2021) (number of individuals)]].


**Root source(s)**
- [[Reference - Living Wage Calculator (Glasmeier, 2022) (data retrieved 26 August 2022)]]
- [[Reference - US Census Bureau dataset “National and State Population Estimates" from database “National Population Totals; 2010-2020” (July 2021)]]
- User assumption of the number of weeks per year, given by [[weeks_per_year=52 (variable) (user assumption) (weeks)#The user-defined number of weeks per year]]
- User assumption of the number of workhours per week, given by [[workhours_per_week=40 (variable) (user assumption) (hours per week)]].

**Object type**
class 'pandas.core.frame.DataFrame'


[^ecoscale]: For a definition of *economies of scale in consumption*, see [['Economies of scale in consumption' as the possible decreases in the cost per person of maintaining a given material standard of living as the number of household members increase (p.1301, Nelson, 1988)]].

[^livwage]: For a definition of *living wage*, see [['Living wage' as the minimum income necessary for an employee to be able to satisfy their basic needs (Wikipedia, 2022)]].
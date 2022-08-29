# minwage_goods_and_services_annual_totalpop_df (variable) (national currency at current prices)
# The total monetary value (measured in national currencies at current prices) of providing everyone in the population (of a given country) with an annual minimum-wage worth of goods and services given the country's average productivity (GDP per hour). Root sources (OECD, 2021), PWT10.0
#github-health-necessary-time
#code-variable #name #code #python #variable

**Name**
`minwage_goods_and_services_annual_totalpop_df`

**Unit**
National currency at current prices.

**Description**
The total monetary value (measured in national currencies at current prices) of providing everyone in the population (of a given country) with an annual minimum-wage worth of goods and services given the country's average productivity (GDP per hour).

**Root source(s)**
- [[Reference - Penn World Table 10.0 (Dataset) (Groningen Growth and Development Centre, 2021)]]
- [[Reference - Minimum Wages at Current Prices in NCU (Database) (OECD, 2021) (accessed 18 April 2022)]]

**Calculation**
`minwage_goods_and_services_annual_totalpop_df = min_grossincome_annual.df  * population.df`

Where
- `min_grossincome_annual` is given by [[min_grossincome_annual (variable) (OECD) (national currencies at current prices)#Minimum annual gross incomes for a number of countries in their national currencies at current prices]], and
- `population` is given by [[population (variable) (Penn World Table 10.0) (number of individuals)]]

**File(s) where variable is declared**
![[minwage_estimate.py]]

**Object type**
class 'pandas.core.frame.DataFrame'

# liv_grossincome_USstates_annual_df (variable) (USD per year, current prices)
#github-health-necessary-time
#code-variable #name #code #python #variable

**Name**
`liv_grossincome_USstates_annual_df`

**Unit**
US dollars per year, current prices.

**Description**
The living wage[^livwage] annual income of a single adult, specified for each US state in units of US dollars per year.

**File(s) where variable is declared**
![[derived_data.py]]

**Calculation**
`liv_grossincome_USstates_annual_df = livwage_USstates_hourly_df * weeks_per_year * workhours_per_week`

Where
- `livwage_USstates_hourly_df` is given by [[livwage_USstates_hourly_df (variable) (Living Wage Calculator, 2022) (USD current prices)]],
- `weeks_per_year` is given by [[weeks_per_year=52 (variable) (user assumption) (weeks)]], and
- `workhours_per_week` is given by [[workhours_per_week=40 (variable) (user assumption) (hours per week)]].

Based on the assumption: [[The living wage model assumes that full-time work is 40 hours per week and 52 weeks per year per adult (p.2, Nadeau and Glasmeier, 2019)]].

**Root source(s)**
- [[Reference - Living Wage Calculator (Glasmeier, 2022) (data retrieved 26 August 2022)]]
- User assumption of the number of weeks per year, given by [[weeks_per_year=52 (variable) (user assumption) (weeks)#The user-defined number of weeks per year]]
- User assumption of the number of workhours per week, given by [[workhours_per_week=40 (variable) (user assumption) (hours per week)]].

**Object type**
class 'pandas.core.frame.DataFrame'



[^livwage]: For a definition of *living wage*, see [['Living wage' as the minimum income necessary for an employee to be able to satisfy their basic needs (Wikipedia, 2022)]].
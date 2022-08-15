# workhours_weekly_avg_df (variable) (hours per week)
# (average weekly hours worked by persons engaged (employees and self-employed))
# Root sources - PWT10.0
#github-health-necessary-time
#code-variable #name #code #python #variable

**Name**
`workhours_weekly_avg_df`

**Unit**
Hours per week.

**Description**
Average weekly hours worked by persons engaged (employees and self-employed)[^personengaged]. 

**Root source(s)**
- [[Reference - Penn World Table 10.0 (Dataset) (Groningen Growth and Development Centre, 2021)]]

**Calculation**
Calculated by dividing [[workhours_annual_avg (variable) (Penn World Table 10.0) (hours per year)#The average number of hours worked per year per person-engaged employees and self-employed]] by [[weeks_per_year=52 (variable) (user assumption) (weeks)]].

**File(s) where variable is declared**
![[derived_data.py]]

**Object type**
class 'pandas.core.frame.DataFrame'


[^personengaged]: *Persons engaged* in the Penn World Tables (starting with version 8) are defined as follows: [['Persons engaged' as the number of employees plus the number of self-employed (for Penn World Tables starting with version 8) (p.22, Feenstra et. al., 2015)]].
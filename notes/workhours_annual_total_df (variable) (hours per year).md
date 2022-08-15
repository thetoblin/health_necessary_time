# workhours_annual_total_df (variable) (hours per year)
# The total number of hours worked (in a given country) by persons engaged (employees and self-employed). Root sources - PWT10.0
#github-health-necessary-time
#code-variable #name #code #python #variable

**Name**
`workhours_annual_total_df`

**Unit**
Hours per year.

**Description**
The total number of hours worked (in a given country) by persons engaged (employees and self-employed).

**Root source(s)**
- [[Reference - Penn World Table 10.0 (Dataset) (Groningen Growth and Development Centre, 2021)]]

**Calculation**
`workhours_annual_total_df = workhours_annual_avg.df * laborforce.df`

Where
- `workhours_annual_avg` is given by [[workhours_annual_avg (variable) (Penn World Table 10.0) (hours per year)#The average number of hours worked per year per person-engaged employees and self-employed]], and 
- `laborforce` is given by [[laborforce (variable) (Penn World Table 10.0) (number of individuals)#Number of persons engaged number of employees plus number of self-employed]].


**File(s) where variable is declared**
![[derived_data.py]]

**Object type**
class 'pandas.core.frame.DataFrame'

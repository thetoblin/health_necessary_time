# workagepop_df (variable) (number of individuals)
# The working-age population (ages of 15-64) in units of number of individuals. Root source (OECD, 2022), PWT10.0
#github-health-necessary-time
#code-variable #name #code #python #variable

**Name**
`workagepop_df`

**Unit**
Number of individuals.

**Description**
The working-age population (ages of 15-64) in units of number of individuals.

**Root source(s)**
- [[Reference - Penn World Table 10.0 (Dataset) (Groningen Growth and Development Centre, 2021)]]
- [[Reference (dataset) - “Working Age Population” (OECD) (accessed June 29, 2022)]]

**Calculation**
`workagepop_df = (workagepop_percent.df / 100) * population.df`

Where
- `workagepop_percent.df` is given by [[workagepop_percent (variable) (OECD) (percent)#The percent of the population that is between the ages of 15-64 of several countries during different years]] and is turned into a fraction by dividing by $100$, and
- `population.df` is given by [[population (variable) (Penn World Table 10.0) (number of individuals)]].


**File(s) where variable is declared**
![[derived_data.py]]

**Object type**
class 'pandas.core.frame.DataFrame'

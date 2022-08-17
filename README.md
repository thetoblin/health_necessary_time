# health_necessary_time

**General description**
Various estimates of the time required to make everyone be in good health.

-------------------------------

**General disclaimer**
The repo-owner is NOT a developer and has probably done plenty of mistakes and/or structured the code in a horrible way. Neither is the repo-owner an economist. All feedback is extremely welcome and encouraged, whether it on the code, how to use git or github, the data sources, or on the analysis. Feel free to make and suggest your own improvements. Constructive criticism is the only way for ideas and persons to improve.

-------------------------------

**Dependencies**
The Python code has been developed (and works) using

Python	     3.9.12
seaborn 	     0.11.2
matplotlib 	 3.5.1
pandas		 1.4.2
numpy		     1.21.5
PIL		         9.0.1

In case it needs to be known, the repo-owner uses Linux.

-------------------------------

**How to generate graph(s)**
Create plots by running the command `python generate_plots.py`.

-------------------------------

**How to review documentation of code and sources**
Sources, as well as code documentation, can be found and reviewed in the `notes` folder. These can be viewed using any text editor, but for best user experience it is recommended to use Obsidian (which can be acquired for free here: https://obsidian.md/).

When reviewing the code, users of Obsidian can enter variable names in the search field to directly find the information related to the given variables (including chains of links to data sources). For example, if the user wants to know more about the variable `workhours_weekly_avg_df` that is defined in `derived_data.py`, simply enter `workhours_weekly_avg_df` in the search field of Obsidian to find the note [[workhours_weekly_avg_df (variable) (hours per week)]].
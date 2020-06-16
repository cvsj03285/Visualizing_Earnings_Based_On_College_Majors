# Visualizing_Earnings_Based_On_College_Majors
In this project, we'll be working with a dataset on the job outcomes of students who graduated from college between 2010 and 2012.

The original data on job outcomes was released by [American Community Survey](https://www.census.gov/programs-surveys/acs/), 
which conducts surveys and aggregates the data. FiveThirtyEight cleaned the dataset and released it on their 
[Github repo](https://github.com/fivethirtyeight/data/tree/master/college-majors).

Each row in the dataset represents a different major in college and contains information on gender diversity, employment rates, median salaries, and more. Some of the columns in the dataset are as follows:
* `Rank` - Rank by median earnings (the dataset is ordered by this column).
* `Major_code` - Major code.
* `Major` - Major description.
* `Major_category` - Category of major.
* `Total` - Total number of people with major.
* `Sample_size` - Sample size (unweighted) of full-time.
* `Men` - Male graduates.
* `Women` - Female graduates.
* `ShareWomen` - Women as share of total.
* `Employed` - Number employed.
* `Median` - Median salary of full-time, year-round workers.
* `Low_wage_jobs` - Number in low-wage service jobs.
* `Full_time` - Number employed 35 hours or more.
* `Part_time` - Number employed less than 35 hours.

## Introduction

In this project, I worked with a dataset on the job outcomes of students who graduated from college between 2010 and 2012. The original data on job outcomes was released by [American Community Survey](https://www.census.gov/programs-surveys/acs/), which conducts surveys and aggregates the data. FiveThirtyEight cleaned the dataset and released it on their [Github repo](https://github.com/fivethirtyeight/data/tree/master/college-majors).

## Variables

Each row in the dataset represented a different major in college and contains information on gender diversity, employment rates, median salaries, and more. Here are some of the columns in the dataset:

| Variables    | Data Types   |
|--------------|--------------|             
|Rank          | int          |             
|Major_code    |int           | 
|Major         |Object        |
|Total         |Float         |
|Men           |Float         |
|Women         |Float         |
|Major_category  | Object     |

Rank                    173 non-null int64
Major_code              173 non-null int64
Major                   173 non-null object
Total                   172 non-null float64
Men                     172 non-null float64
Women                   172 non-null float64
Major_category          173 non-null object
ShareWomen              172 non-null float64
Sample_size             173 non-null int64
Employed                173 non-null int64
Full_time               173 non-null int64
Part_time               173 non-null int64
Full_time_year_round    173 non-null int64
Unemployed              173 non-null int64
Unemployment_rate       173 non-null float64
Median                  173 non-null int64
P25th                   173 non-null int64
P75th                   173 non-null int64
College_jobs            173 non-null int64
Non_college_jobs        173 non-null int64
Low_wage_jobs           173 non-null int64

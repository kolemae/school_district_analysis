# School District Funding and Standardized Test Analysis
Project using Pandas and Jupyter Notebook to clean, analyze, format, and display school district data.

## Table of contents
* [Overview of Project](#overview-of-project)
* [Resources](#resources)
* [School District Results](#school-district-results)
* [Summary](#summary)

## Overview of Project
I was tasked with assisting Maria, the Chief Data Scientist for a city school district, with analyzing data on student funding and students' standardized test scores. We aggregated data and showcased trends in school performance to assist the school board and superintendent with budgeting and prioritization within the district. For this project we:
- Created a development environment that runs Python 3.7
- Cleaned student names to match district records
- Replaced Thomas High School's 9th grade results with NaN's
- Created a district summary DataFrame
- Created a school summary DataFrame
- Determined the top 5 performing schools, based on overall passing rate
- Determined the bottom 5 performing schools, based on overall passing rate
- Calculated the average math score for each grade level from each school
- Calculated the average reading score for each grade level from each school
- Organized the scores by school spending per student
- Organized the scores by school size
- Organized the scores by school type

### Resources
- Data source: schools_complete.csv, students_complete.csv
- Software: Anaconda 2021.11, Python 3.7.11, Jupyter Notebook

## School District Results
The district summary from the original [PyCitySchools](PyCitySchools.ipynb) to the final [PyCitySchools_Challenge](PyCitySchools_Challenge.ipynb) is affected by slightly lower average scores, as seen in the following images:

- Original Disctrict Summary
![Original District Summary](/Resources/districtsummary.png)

- Final Disctrict Summary
![Final District Summary](/Resources/districtsummary_final.png)

For the school summary, Thomas High School's average and passing percentages are slightly lower than the original:

- Original School Summary
![Original School Summary](/Resources/perschoolsummary.png)

- Final School Summary
![Final School Summary](/Resources/perschoolsummary_final.png)

## Summary
Seen in the updated analysis after replacing Thomas High School's ninth grade scores with NaN's:
1. Lowered average and passing percentages for Thomas High School
2. Lowered average and passing percentages District-wide
3. Thomas High School's overall performance remained the same despite percentage changes
4. No change in scores by school spending, size, and type

Changes are most evident pertaining to Thomas High School, but minor or non-evident in the larger data view.

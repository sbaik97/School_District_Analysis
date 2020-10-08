# School_District_Analysis
Schooldistrict and performance alyses by using the Python and Jupytor Notebook

## Project Background


* Use Python and Pandas library to analyze school distrct data and showcase trends in school performance based on key metrics.
* Use Jupyter Notebook to visualize data outcomes as table format.
* Here is the list of deliverables for the analysis of the school district:

    - Top 5 and bottom 5 performing schools, based on the overall passing rate
    - The average math score received by students in each grade level at each school
    - The average reading score received by students in each grade level at each school
    - School performance based on the budget per student
    - School performance based on the school size 
    - School performance based on the type of school

* This analysis assists the school board and district level in making desicions of budgets and priorities.

## The process of project

* Read raw data in csv file.
* Clean and inspect data, correct inappropriate data.
* Merge datasets to create new DataFrame gathering more information.
* Perform calculations for key metrics use groupby() function.
* Visualize data with tables to tell story and showcase trends.

## Software/Tools/Libraries
* Python 3.7.6, Jupyter Notebook 6.1.4
* Data Source: schools_complete.csv, students_complete.csv, 

----------------------

# Challenge

## Goals

* Comparing two analysis results after removing the ninth-grade math and reading scores from Thomas High School, makeing cohesive conclusions using the Pandas loc method in Jupyter Notebook.


## Results

There are 15 Analysis tables are in the Image folder. Attached are a few examples of analysis. 

1. The *Thomas_9th_info* is information about studnet data after removing the ninth-grade math and reading scores from Thomas High School.

![Thomas_9th_info](/Images/cleaned_Thomas_9th.PNG)

-----------------------

2. The *final_compare_summaries* are the two distric summary tables to see the average socres, passing percentage of math, radeaing, and oaverall scores by comparing between before and after removing the ninth-grade math and reading scores from Thomas High School.

District_summary without change
![final_compare_summaries I](/Images/original_distric_summary.PNG)
District_summary with change
![final_compare_summaries I](/Images/cleaned_distric_summary.PNG)

3. The *final_compare_summary* is the two schoool summary tables groupby each school, comparing between before and after removing incorrect data. The passing percentage rate, including both math and reading as well as overall passing percentage, are significantly decreases for Thomas High School

Per_school_summary without change
![final_compare_summary I](/Images/original_per_school_summary.PNG)
Per_school_summary with change
![final_compare_summary I](/Images/cleaned_per_school_summary.PNG)

## Conclusion

After removing the ninth-grade math and reading scores from Thomas High School, it affacts summary tables by slightly reducing the average scores and enomous decreasing for the passing percentage rate, including both math and reading passing percentage as well as overall passing percentage.

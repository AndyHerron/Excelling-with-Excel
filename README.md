# Excelling-with-Excel
working on Excel projects


## Creating the raw data to use.
I created a Python file in Jupiter Notebooks to create a dataset.  I wanted a fairly large dataset to play with, \  
so I used numpy and pandas to create 12,000 random numbers between zero and 1, formatted into 12 columns and \  
1000 rows.  This could represent monthly data points for a year, from 1000 different sources.  Maybe it's scientific data,
or it could represent sales numbers/1000 from 1000 different stores.

I named the columns for each month of the year, and then exported the dataframe to a .CSV file.

## Within Excel

1. I created new columns to show the sum, average, minimum & maximum values for each row.
2. Then I applied conditional formatting to each of the new columns.
	- Solid data bars in the Total column easily show which rows had higher sums.
	- If any row's average was below .5 then it's number is shown in red.
	- The minimum data point for each row is shown in red if it is in the bottom 10%.
	- The maximum data point for each row is show in green if it is in the top 10%.

## GradeBook excercise
Create a formula that calculates the final grade for a student based upon their previous exams and papers.
When making this calculation:
  * Every paper and exam should be considered equal in weight
  * Each one should comprise one-fourth of a student's overall grade
  * Round the result to the nearest integer
  * Using conditionals, create a formula that returns `PASS` if a student's final grade is greater than or equal to 60. If the student's final grade is below 60, your formula should return `FAIL`.
** BONUS **
* Create a nested `IF()` formula which returns a letter grade based on a student's final grade.
  * Greater than or equal to 90 = `A`
  * Greater than or equal to 80 and less than 90 = `B`
  * Greater than or equal to 70 and less than 80 = `C`
  * Greater than or equal to 60 and less than 70 = `D`
  * Anything less than 60 = `F`

## GradeCharts
Create bar and line charts that visualize the grades of students over the course of a semester.
* Create bar graphs that visualize the grades of all students in the class, one graph for every month.
* Create a line graph that shows the grades for all the student over the semester.
  * Use filtering in the line graph to allow you to drill down to a specific student's progress throughout the semester.
** Hint **
* When duplicating bar graphs, it pays to get the formatting and look of the chart where you want it for the first graph (e.g. for January), and to then copy that chart and re-select the data for the subsequent copies (keeping the style and format, but just changing the data).


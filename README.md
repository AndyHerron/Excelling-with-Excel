# Excelling-with-Excel
working on Excel projects


## Creating the raw data to use.
I created a Python file in Jupiter Notebooks to create a dataset.  I wanted a fairly large dataset to play with,\
so I used numpy and pandas to create 12,000 random numbers between zero and 1, formatted into 12 columns and \
1000 rows.  This could represent monthly data points for a year, from 1000 different sources.  Maybe it's scientific data,\
or it could represent sales numbers/1000 from 1000 different stores.

I named the columns for each month of the year, and then exported the dataframe to a .CSV file.\

## Within Excel

1. I created new columns to show the sum, average, minimum & maximum values for each row.
2. Then I applied conditional formatting to each of the new columns.
	- Solid data bars in the Total column easily show which rows had higher sums.
	- If any row's average was below .5 then it's number is shown in red.
	- The minimum data point for each row is shown in red if it is in the bottom 10%.
	- The maximum data point for each row is show in green if it is in the top 10%.

3. Creating Pivot Tables

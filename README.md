# pandas-challenge
homework assignment using pandas for UCF Boot Camp
To do list:

District Summary:
	- Calculate
		- Total Number of Schools
		- Total Students
		- Total Budget
		- Average Math Score
		- Average Reading Score
		- Passing Math Percentage
		- Passing Reading Percentage
		- Overall Passing Rate
School Summary:
	- Needs to have
		- Names
		- Types
		- Total Students
		- Total School Budget
		- Per Student Budget
		- Average Math Score
		- Average Reading Score
		- Passing Math Percentage
		- Passing Reading Percentage
		- Overall Pass Rate
		- (Note): These are series that are added to new DataFrame by School Name
Highest Performing Schools:
	- Do:
		-Sort Schools by Overall Passing in decending order (high to low)
		-Put it in a new DataFrame
Lowest Performing Schools:
	- Do:
		-Sort Schools by Overall Passing in ascending order (low to high)
		-Put it in a new DataFrame
Math Scores by Grade:
	- Do:
		- Divide by Grade
		- Isolate Scores (groupby)
		- combine scores into DataFrame
Reading Scores by Grade:
	- Do:
		- Divide by Grade
		- Isolate Scores (groupby)
		- combine scores into DataFrame
Scores by School Spending:
	- Do:
		- Create bins
		- Create labels
		- make new df using school summary
		- make new column using per capita series, bins, and labels (.cut)
		- Calculate averages of each column (groupby)
		- Add to new DataFrame
Scores by Size:
	- Do:
		- Create bins
		- Create labels
		- make new df using school summary
		- make new column using per capita series, bins, and labels (.cut)
		- Calculate averages of each column (groupby)
		- Add to new DataFrame
Scores by School Type:
	- Do:
		-Get averages based off school type (groupby)
		- Add to new DataFrame
		
References: 

PyCitySchools_starter.ipynb (starter code provided)

https://stackoverflow.com/questions/72223610/dropping-invalid-columns-futurewarning

https://pandas.pydata.org/docs/reference/api/pandas.Series.value_counts.html

https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.groupby.html

https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.sort_values.html

https://pandas.pydata.org/docs/reference/api/pandas.cut.html

https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html

https://pandas.pydata.org/docs/reference/api/pandas.unique.html

https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.mean.html

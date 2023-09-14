# pandas-challenge
Module 4 Challenge - using Pandas DataFrame to analyze data.

- <b>Notes to Graders:</b> Please refer to the first Markdown in the <code>PyCitySchools_analysis.ipynb</code> for the final analysis.

# Background
You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

# Instructions
Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.

- <b>District Summary:</b> Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame. Include the following:
    - Total number of unique schools
    - Total students
    - Total budget
    - Average math score
    - Average reading score
    - % passing math (the percentage of students who passed math)
    - % passing reading (the percentage of students who passed reading)
    - % overall passing (the percentage of students who passed math AND reading)

- <b>School Summary:</b> Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school. Include the following:
    - School name
    - School type
    - Total students
    - Total school budget
    - Per student budget
    - Average math score
    - Average reading score
    - % passing math (the percentage of students who passed math)
    - % passing reading (the percentage of students who passed reading)
    - % overall passing (the percentage of students who passed math AND reading)

- Determine <b>Highest-Performing Schools (by % Overall Passing)</b> by sorting the schools by <code>% Overall Passing</code> in descending order and display the top 5 rows.

- Determine <b>Lowest-Performing Schools (by % Overall Passing)</b> by sorting the schools by <code>% Overall Passing</code> in ascending order and display the top 5 rows.

- Determine <b>Math Scores by Grade</b> by performing the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

- Determine <b>Reading Scores by Grade</b> by creating a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

- Create a DataFrame for <b>Scores by School Spending</b> by creating a table that breaks down school performance based on average spending ranges (per student) that includes the following:
    - Average math score
    - Average reading score
    - % passing math (the percentage of students who passed math)
    - % passing reading (the percentage of students who passed reading)
    - % overall passing (the percentage of students who passed math AND reading)

- Determine <b>Scores by School Size</b> using the provided bins and labels.

- Determine the <b>Scores by School Type</b>.

# References
- Helpful links used to help with functions and syntaxes:
    - https://stackoverflow.com/questions/50490540/replace-a-character-in-a-python-dataframe-column
    - https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html
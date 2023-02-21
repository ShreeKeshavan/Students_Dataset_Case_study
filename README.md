# Students_Dataset_Case_study
## Analysis of Two CSV Files
This project involves working with two CSV files and performing various data analysis tasks on them.

## Problem Statement
⚫ Import necessary libraries

⚫ Merge those two CSV files (after getting as dataframes, get them as a single dataframe)

⚫ Take each CSV file, split that CSV file into multiple categories

⚫ Consider if the codekata score exceeds 15000 points (present week) then make a CSV on those observations as Exceeded expectations.csv

⚫ If codekate score < 7000 (Unsatisfactory.csv)

⚫ Average of previous week geekions vs this week geekions (i.e Previous Geekions vs CodeKata Score)

⚫ No of students participated

⚫ Average completion of python course or my_sql or python english or computational thinking

⚫ Rising star of the week (top 3 candidate who performed well in that particular week)

⚫ Shining stars of the week (top 3 candidates who have highest geekions)

⚫ Department wise toppers (horizontal bar graph or any visual representations of your choice)

## Solution
⚫ To start the analysis, we need to import the necessary libraries. For this project, we will use pandas and numpy libraries for data analysis.

⚫ After importing the libraries, we will read the two CSV files into pandas dataframes and merge them into a single dataframe.

⚫ Next, we will split each CSV file into multiple categories using pandas' groupby function. This will allow us to perform more granular analysis on the data.

⚫ We will then create a new CSV file for the students who have exceeded expectations in the present week (codekata score > 15000).

⚫ Similarly, we will create another CSV file for the students who have scored below satisfactory (codekata score < 7000).

⚫ We will calculate the average of the previous week's geekions and this week's codekata score using pandas' mean function.

⚫ We will then count the number of students who participated in the codekata using pandas' count function.

⚫ To calculate the average completion of each course, we will group the data by the course name and calculate the mean of the completion percentage.

⚫ To find the rising stars of the week, we will sort the data by the percentage improvement in geekions from the previous week and select the top three students.

⚫ To find the shining stars of the week, we will sort the data by the total geekions and select the top three students.

⚫ Finally, we will create a horizontal bar graph to show the department-wise toppers.

## Conclusion
⚫ In this project, we learned how to work with CSV files and perform various data analysis tasks using pandas and numpy libraries. We split the data into multiple categories, created new CSV files, calculated averages and counts, and identified the top performers. The analysis will provide valuable insights into the performance of the students and help in identifying areas for improvement.

⚫ This README file provides a high-level overview of the project and the approach taken to solve the problems mentioned in the problem statement. For detailed code and outputs, please refer to the Jupyter Notebook or Python script included in the repository.

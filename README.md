# pandas-challenge

## Background

Having spent years analyzing financial records for big banks, you've finally scratched your idealistic itch and joined the education sector. Your latest role is Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

### My analysis is at the bottom! 


### District Summary

Create a high-level snapshot, in a DataFrame, of the district's key metrics, including the following:

* Total schools
* Total students
* Total budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### School Summary

Create a DataFrame that summarizes key metrics about each school, including the following:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Highest-Performing Schools (by % Overall Passing)

Create a DataFrame that highlights the top 5 performing schools based on % Overall Passing. Include the following metrics:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)


### Lowest-Performing Schools (by % Overall Passing)

Create a DataFrame that highlights the bottom 5 performing schools based on % Overall Passing. Include the following metrics:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Math Scores by Grade

Create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade

Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending

Create a table that breaks down school performance based on average spending ranges (per student). Use your judgment to create four bins with reasonable cutoff values to group school spending. Include the following metrics in the table:

* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Scores by School Size

Create a table that breaks down school performance based on school size (small, medium, or large).
### Scores by School Type

Create a table that breaks down school performance based on type of school (district or charter).
### Report Analysis

This report is an analysis of the data generated from PyCitySchools from the csv files named schools_complete.csv and students_complete.csv. The two csv files were merged with a left join in a data frame, which was then further formatted/split in various ways to meet the criteria. Given the data provided we can draw a clear conclusion that more funding does not mean better overall grades. I am not sure if we can draw a clear conclusion that the cause of poor grades is indeed high funding, but the clear conclusion here is that charter schools simply perform better than District schools which on average spend less per student. Looking deeper at the data, we can clearly draw the conclusion that charter schools teach math differently which leads to their lowest passing percentage which is 93%(rounded) compared to the highest district passing rate which is 68.3%. That is a very large gap, and plummets the Districts overall passing rate, as the overall reading rate is within 4 percentage points across both charter and district schools. Another thing to note is that the grade one is in doesn’t change really change the passing rates, all increases and decreases are within one or two percentage points, meaning that the school you’re at is the more likely indicator for whether you’re going to pass math(lol). 
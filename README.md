# Pandas Challenge

## Background
You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

## Instructions
Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.

## District Summary
Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.

Include the following:

- Total number of unique schools
- Total students
- Total budget
- Average math score
- Average reading score
- % passing math (the percentage of students who passed math)
- % passing reading (the percentage of students who passed reading)
- % overall passing (the percentage of students who passed math AND reading)

<img width="990" alt="Screenshot 2023-05-03 at 4 23 24 PM" src="https://user-images.githubusercontent.com/121995835/236041118-8901a0e0-2813-452c-9fe6-c1e2a17feb8a.png">

## School Summary

Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.

Include the following:

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

<img width="1023" alt="Screenshot 2023-05-03 at 4 24 28 PM" src="https://user-images.githubusercontent.com/121995835/236041399-e5fe58c6-bcca-4740-ac03-fc626c916510.png">

## Highest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows.

Save the results in a DataFrame.

<img width="741" alt="Screenshot 2023-05-03 at 4 25 29 PM" src="https://user-images.githubusercontent.com/121995835/236041615-8ae543eb-cea8-4cac-8208-bf0c4a0827b7.png">

## Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.

Save the results in a DataFrame.

<img width="741" alt="Screenshot 2023-05-03 at 4 26 23 PM" src="https://user-images.githubusercontent.com/121995835/236041768-af84b083-f10b-4bd2-88b5-616d0e72e27e.png">

## Math Scores by Grade
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

<img width="531" alt="Screenshot 2023-05-03 at 4 27 02 PM" src="https://user-images.githubusercontent.com/121995835/236041905-e8b72de3-dd20-46f4-b9e6-325b290d6d93.png">

## Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

<img width="531" alt="Screenshot 2023-05-03 at 4 27 26 PM" src="https://user-images.githubusercontent.com/121995835/236041998-cd06d844-af9f-4966-b7ea-7ea9dadd65f8.png">

## Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student).

Use pd.cut to categorize spending based on the bins.

<img width="472" alt="Screenshot 2023-05-02 at 3 38 41 ![Uploading Screenshot 2023-05-03 at 4.28.02 PM.png…]()
PM" src="https://user-images.githubusercontent.com/121995835/235770012-facca13b-4c92-417e-87ff-3d1ce9b4bfc9.png">

Include the following metrics in the table:

- Average math score
- Average reading score
- % passing math (the percentage of students who passed math)
- % passing reading (the percentage of students who passed reading)
- % overall passing 

<img width="708" alt="Screenshot 2023-05-03 at 4 39 06 PM" src="https://user-images.githubusercontent.com/121995835/236044392-5e064c20-2aca-4a75-8899-c3ad1b8e0ca5.png">

## Scores by School Size
Create a DataFrame that breaks down school performance based on school size (small, medium, or large).

<img width="714" alt="Screenshot 2023-05-03 at 4 43 41 PM" src="https://user-images.githubusercontent.com/121995835/236045255-facfcd7a-42de-44b2-820c-917e2281858e.png">

## Scores by School Type
Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.

This new DataFrame should show school performance based on the "School Type".

<img width="714" alt="Screenshot 2023-05-03 at 4 41 42 PM" src="https://user-images.githubusercontent.com/121995835/236044837-2a55bc34-cde5-4737-b0b6-dfda3a090929.png">

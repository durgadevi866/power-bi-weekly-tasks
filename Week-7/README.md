# Week 7 – Student Performance Data Cleaning & Transformation

## Overview

This Week 7 project focuses on cleaning, transforming, modeling, and analyzing the Student Performance dataset using Power BI and Power Query. The dataset contains student demographic information, test preparation details, and Math, Reading, and Writing scores.

## Objectives

- Import and inspect the Student Performance dataset
- Check and verify data types
- Standardize Parental Education values
- Create Total Marks and Average Total
- Create Performance Grade and Pass/Fail Result
- Create a unique Student ID
- Create and transform the Student Marks table
- Unpivot subject score columns
- Create DAX measures
- Establish and verify table relationships
- Validate the transformed dataset

## Data Transformation

The following transformations were performed using Power Query:

1. Checked the data types of all columns.
2. Standardized the Parental Education column.
3. Created a Total Marks column by adding Math, Reading, and Writing scores.
4. Created an Average Total column by dividing Total Marks by 3.
5. Created a Performance Grade column using conditional logic.
6. Created a Result column to classify students as Pass or Fail.
7. Created a unique Student ID using an Index Column.
8. Duplicated the dataset and created the Student Marks table.
9. Kept Student ID, Math Score, Reading Score, and Writing Score in Student Marks.
10. Unpivoted the three subject score columns into Subject and Score.

## DAX Measures

The following DAX measures were created:

- Average Math Score
- Average Reading Score
- Average Writing Score
- Overall Average Score
- Overall Pass %

## Data Model

Two tables were prepared:

- StudentsPerformance
- Student Marks

The tables were linked using Student ID with a one-to-many relationship.

## Validation

The results were validated by checking:

- Total Marks calculation
- Average Total calculation
- Performance Grade classification
- Pass/Fail Result
- Unpivoted subject scores
- DAX measure results
- Student ID relationship

## Project Files

- Week-7-Student-Performance-PowerBI.pbix
- Week-7-Student-Performance-Report.pdf
- README.md

## Conclusion

Week 7 successfully transformed the Student Performance dataset into a clean and structured Power BI model. Calculated columns, performance classifications, an unpivoted subject-level table, DAX measures, and table relationships were created and validated. The prepared dataset is ready for the Week 8 Student Performance Dashboard.

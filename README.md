# Library Books Analysis System Library Books Analysis System

## Overview
This project is a beginner Python data analysis project that reads library book data from a CSV file and generates a summary report. The goal of the project was to practise working with files, loops, dictionaries, and basic data analysis techniques using Python.

## Features

Read and process data from a CSV file
Skip the header row when reading the file
Extract book titles, genres, ratings, page counts, and borrow counts
Calculate the average rating
Find the book with the highest rating
Find the median page count
Count the number of books in each genre
Identify the most borrowed book
Generate a summary report and save it to a text file
Visualise borrow counts using a bar chart

## Technologies Used

Python
Pandas
NumPy
Matplotlib
CSV Files

## How the Project Works

Open and read the CSV file containing library book data.
Skip the header row.
Clean each line by removing unnecessary spaces.
Split each line into separate values using commas.
Extract the required information such as titles, genres, ratings, page counts, and borrow counts.
Perform calculations and analysis on the data.
Save the analysis results into a report file.
Generate a bar chart showing borrow counts per book.

## Sample Output
# LIBRARY BOOKS REPORT
=====================
- Total Number of Books: 10
- Average Rating: 4.23
- Highest Rated Book: Baking Masterclass (4.8)
- Median Pages: 295.0
- Most Borrowed Book: Crime Scene (70)

## Books Per Genre:
- Technology: 2
- Mystery: 2
- Science Fiction: 2
- Cooking: 2
- History: 2
  
## What I Learned
Through this project, I improved my understanding of:

File handling using with open()
Lists and dictionaries
Counting items using dict.get()
Sorting lists and calculating medians
Data aggregation (average, maximum, median)
Using Pandas for grouping and analysis
Creating visualisations with Matplotlib
Writing results to external text files

## Future Improvements

Add more visualisations (e.g. ratings by genre).
Store the data in a SQL database instead of a CSV file.
Build a simple user interface for the system

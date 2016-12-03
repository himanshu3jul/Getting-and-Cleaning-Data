# Getting and Cleaning Data - Course Project

This is the project for the Getting and Cleaning Data Coursera course. The R script, `run_analysis.R`, does the following:

1. Download the dataset
2. Loads the activity and feature info
3. Loads both the training and test datasets
4. Loads the activity and subject data for each dataset, and merges these columns with the dataset
5. Merges the above two datasets
6. Converts the `activity` and `subject` columns into factors
7. Creates a tidy dataset (tidy_data.txt) that consists of the average (mean) value of each variable for each subject and activity pair.

# Readme file to the the assignment of Getting and Cleaning Data
This repo contains mainly the script run_analysis.R.

run_analysis.R produces a tidy subset of the UCI HAR dataset. In particular, the script contains 6 steps:

1. Load all data and provide tidy column names
2. Merge data sets to a single data set (structure: subject_id, activity_label, measured_values)
3. Extract the columns that contain means and standard deviations
4. Replace activity codes by descriptive labels
5. Name the features (i.e. the column names in step 1)
6. For each combination of subject_id and activity_label, calculate mean of each column.

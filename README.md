# Coursera - Getting and Cleaning Data Course Project
This repository hosts the R code and documentation files for the course project for the "Getting and Cleaning Data".

The data being used is: [Human Activity Recognition Using Smartphones](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

## Repository Contents

`CodeBook.md` is a code book that describes the variables, the data, and any transformations or work performed to clean up the data.

`run_analysis.R` does the following:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

`averages_data.txt` is the output of the 5th step of the R program.

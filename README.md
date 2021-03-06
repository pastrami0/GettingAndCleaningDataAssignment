# GettingAndCleaningDataAssignment

Welcome to my Final Project for the Getting and Cleaning Data course.

### Contents:
 - README.md: this file
 - codebook.md: code book
 - UCIHAR_tidy.txt: tidy data set with the average of each variable for each activity and each subject
 - run_analysis.R: script to run analysis
 
### Assignment:
 
One of the most exciting areas in all of data science right now is wearable computing - see for example this article . Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

You should create one R script called run_analysis.R that does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

### Analysis

The run_analysis.R script will read in all of the UCI HAR data; combine into one large training set; select columns carrying mean or standard deviation data; "gather" into one tidy dataset; convert activity numbers to labels; calculate means for each variable for each subject for each activity; and write the calculated means to a new table. 

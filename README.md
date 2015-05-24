## Getting and Cleaning Data Coursera - Johns Hopkins University : Course Project 


The data is available at the UCI HAR Dataset directory: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

* Instructions:

    You should create one R script called run_analysis.R that does the following. 

    Merges the training and the test sets to create one data set.
    
    Extracts only the measurements on the mean and standard deviation for each measurement. 
    
    Uses descriptive activity names to name the activities in the data set
    
    Appropriately labels the data set with descriptive variable names. 

    From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each     activity and each subject.


* Steps:

    Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder     on your local drive.

    Put Run_Analysis.R into the folder

    In RStudio: setwd("the path) and after: source("Run_Analysis.R")

    Use data <- read.table("data_set_with_the_averages.txt") to read the data. The data set is composed by 180 rows         corresponding to 30 subjets and 6 activities.

# Getting-and-Cleaning-Data-Final-Project
Repo for the submission of the course project for the Johns Hopkins Getting and Cleaning Data course.

#Overview
This repository hosts the R code and documentation files for the Data Science's track course "Getting and Cleaning data", available in coursera.
This particular project serves to demonstrate the collection and cleaning of a tidy data set that can be used for subsequent analysis. A full description of the data used in this project can be found at The UCI Machine Learning Repository

The source data for this project can be found here.

#Making Modifications to This Script

Once you have obtained and unzipped the source files, you will need to make one modification to the R file before you can process the data. Note that on line 26 of run_analysis.R, you will set the path of the working directory to relect the location of the source files in your own directory.

#Project Summary

The following is a summary description of the project instructions

You should create one R script called run_analysis.R that does the following. 

1. Merges the training and the test sets to create one data set. 
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set 
4. Appropriately labels the data set with descriptive activity names. 
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

#Files

CodeBook.md describes the variables, the data, and any transformations or work that was performed to clean up the data.

run_analysis.R is the R sript that performs the analyses described in the 5 steps.It can be launched in RStudio by just importing the file.

The output of the 5th step was uploaded in the course project's form.

# Getting and Cleaning Data Course Project

This repository hosts the R code for the Getting Clean Data Assignment

## Files

`CodeBook.md` describes the how to use all this, variables, the data, and any transformations or work that was performed to clean up the data.

`run_analysis.R` contains all the code to perform the analyses described in the 5 steps.

## R Script Explanation

File with R code "run_analysis.R" perform 5 following steps:   
1. Merging the training and the test sets to create one data set   
  1 Reading files    
    Reading trainings tables   
    Reading testing tables   
    Reading feature vector   
    Reading activity labels   
  2 Assigning column names   
  3 Merging all data in one set   
2. Extracting only the measurements on the mean and standard deviation for each measurement   
  1 Reading column names  
  2 Create vector for defining ID, mean and standard deviation   
  3 Making nessesary subset from setAllInOne   
3. Using descriptive activity names to name the activities in the data set   
4. Appropriately labeling the data set with descriptive variable names   
5. Creating a second, independent tidy data set with the average of each variable for each activity and each subject   
  1 Making second tidy data set   
  2 Writing second tidy data set in txt file   

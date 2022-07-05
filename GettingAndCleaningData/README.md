# Getting and Cleaning Data Course Project

The purpose of this course project is to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. The data set is shared through the UCI Machine Learning Repository, and more detailed information can be found here: [Human Activity Recognition Using Smartphones](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones).

## Files

1.  `run_analysis.R` is the R script that does the following:

    -   Merges the training and the test sets to create one data set
    -   Extracts only the measurements on the mean and standard deviation for each measurement
    -   Uses descriptive activity names to name the activities in the data set
    -   Appropriately labels the data set with descriptive variable names
    -   From the data set in the above step, creates a second, independent tidy data set with the average of each variable fo each activity and each subject

2.  `OutputData.txt` is the final tidied data set from the last step generated by the 'run_analysis.R' script.

3.  `CookBook.md` is the code book that indicates all the variables and summaries calculated, along with units, and any other relevant information.
# There are comments with each line so that you can understand the code.

datalink <- https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
dataDescriptionLink <- http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

## 1.How to run the script "run_analyis.R"
1. copy the three R files present in this repository in your folder which you get after extracting the file that is "UCI HAR Dataset"
2. In Rstudio set the folder "UCI HAR Dataset" as your working directory.  
3. In Rstudio type source("run_analysis.R")

## 2.Labels for activities
1.  W for walking
2.  WU for walking upstair
3.  WD for Walking Downstairs
4.  SI for sitting
5.  ST for standing
6.  L for Laying

## 3.Column variables are same as described in the file "features.txt"

## 4.The main datasets
1.  combDataSet  --> it is a data set which is a combination of subjects,activities,test data,train data and the variables are also present.

2.  DataSetOfMean--> it is a data set which contains Mean of mean and std variable and is summarised by each subjects' 6 different 
                   activities.

## 5. Information about R files
1. tidyingTrainData.R contain code for arranging training data.
2. tidyingTestData.R contain code for arranging training data.

note: the test data R file should be run first then the training data R file should be run because they both are linked.

----------------------------------------------------------------------------------------------------------------------------------------

## Objectives:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

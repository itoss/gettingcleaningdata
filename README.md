Getting and Cleaning Data

Assignment:
You should create one R script called run_analysis.R that does the following. 
1.	Merges the training and the test sets to create one data set.
2.	Extracts only the measurements on the mean and standard deviation for each measurement. 
3.	Uses descriptive activity names to name the activities in the data set
4.	Appropriately labels the data set with descriptive variable names. 
5.	From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject

Run_Analysis description: 
Load (data.table) and (dplyr) libraries 
Read name of features and activities  
Read training and test data
1.	Merge training/test into one data set and name columns 
2.	Extract mean and standard deviation for each measurement 
3.	Change activity names to descriptive names 
4.	Label data set with descriptive variable names
5.	Create new tidy data set, compute average of each variable for activity/subject

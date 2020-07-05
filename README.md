# Getting-and-cleaning-data
#course project
You should create one R script called run_analysis.R that does the following.
1.Merges the training and test sets to create one data set.
2.Extracts only the measurements on the  mean and standard deviation for each measurement.
3.Uses descriptive activity names to name the activities in data set.
4.Appropriately labels the data set with descriptive activity names.
5.Creates a second ,independent tidy data set with average of each variable for each activity and each subject.
#Steps to work on this course project
1.Download the data source and put into folder on your local drive .you will have UCI HAR data set folder.
2.put run_analysis.R in the parent folder of UCI HAR Dataset,then set it as your working directory using setwd() function in Rstudio.
3.Run source("run_analysis.R"),then it will generate a new file tiny.data.txtin your working directory.
#Dependencies
run_analysis.R will help you to install the dependencies automatically.It depends on reshape2 and data.table.
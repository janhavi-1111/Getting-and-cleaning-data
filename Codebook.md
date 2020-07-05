#Codebook
This is a code book that describes the variables,the data,and any transformations or work that you performed to clean up the data.
#The data source
Original data:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
Original description of data:
http://archieve.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
#Dataset Information
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years.Each person performed six activities(WALKING,WALKING_UPSTAIRS,WALKING_DOWNSTAIRS,SITTING,STANDING,LAYING)wearing smartphone on waist.Using its embedded accelerometer and gyroscope,we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz,The experiments have been video-recorded to label the data manually.The obtained dataset has been randomly partitioned into two sets,where 70% of the volunteers was selected for generating the training data and 30% the test data.
#The data 
It includes the folloing files:
1.'README.txt'
2.'features_info.txt':shows info about variables used on feature vector.
3.'features.txt':list of all features.
4.'activity_labels.txt':links the class labels with their activity names.
5.'train/X_train.txt':training set.
labels.
7.'test/X_test.txt':test set.
8.test/Y_test.txt':test labels.
#TRANSFORMATION DETAILS:
There are 5 major parts:

1.Merges the training and test sets to create one data set.
2.Extracts only the measurements on mean and standard deviation for each measurements.
3.Uses descriptive activity names to name the activities in data set .
4.Appropriately labels the data set with descriptive activity names.
5.Creates second independent and tidy data set with average of each variable for each activity and each subject.

